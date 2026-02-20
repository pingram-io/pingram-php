# Pingram PHP SDK

Official PHP SDK for Pingram. Send notifications via Email, SMS, Push, In-App, and more from your PHP application.

## Requirements

- PHP 8.1+
- Composer
- [guzzlehttp/guzzle](https://github.com/guzzle/guzzle) (installed via Composer)

## Installation

```bash
composer require pingram/php
```

Or add to your `composer.json`:

```json
{
  "require": {
    "pingram/php": "^0.1"
  }
}
```

Then run `composer install`.

## Quick start

Use the **Pingram\Client** with your **API key**, then call `send()` or the namespaced APIs (`getDomains()`, `getSender()`, etc.).

```php
<?php

require_once __DIR__ . '/vendor/autoload.php';

use Pingram\Client;
use Pingram\Model\SenderPostBody;

$client = new Client('pingram_sk_...');

// Send a notification (delegates to the default/sender API)
$body = new SenderPostBody([
    'notification_id' => 'your_notification_id',
    'to' => ['id' => 'user_123'],
]);
$response = $client->send($body);

// Or use namespaced APIs: $client->getDomains(), $client->getSender(), etc.
// $senders = $client->getDomains()->domainsListDomains();
```

You can override the base URL by passing a second argument: `new Client('pingram_sk_...', 'https://api.example.com')`.

## What can I call?

- **`$client->send($body)`** – send a notification (high-level).
- **`$client->getDomains()`**, **`$client->getSender()`**, **`$client->getAccount()`**, etc. – low-level API objects. Each has methods matching the API (e.g. `domainsListDomains`, `senderTestEmail`).

For the full list of methods on each API, see **API_REFERENCE.md** in this directory (generated when you run codegen).

## Generating the SDK

From the `serverless/` directory (or repo root with correct paths):

```bash
npm run codegen:sdk
```

This generates the OpenAPI spec and all SDKs, including PHP, into `sdks/php/generated/`.

**Adding new endpoints:** Update the OpenAPI spec (new paths and tags), then run `npm run codegen:sdk`. The wrapper and API reference are derived from the spec, so new APIs and methods appear automatically.

## Links

- [Documentation](https://docs.pingram.io)
