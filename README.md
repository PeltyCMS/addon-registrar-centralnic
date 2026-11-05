# CentralNic Reseller

Register and renew domains with CentralNic Reseller

Official **domain registrar** for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) — identifier `registrar-centralnic`.

## Why this addon

Resellers who sell domains next to hosting and need automated register / renew.

## Features

- Availability checks against the official **CentralNic Reseller** API
- Register, renew and transfer domains from Pelty orders
- Nameserver and contact updates where the API allows
- TLD costs sync into Pelty pricing
- Sandboxed WASM registrar — credentials stay in the panel

## How it works

1. Install **CentralNic Reseller** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/registrar-centralnic) (or Pelty Admin → Addons → Marketplace).
2. Open Pelty Admin and enter your CentralNic Reseller credentials in the addon settings.
3. Attach it to the products / forms / login flows you care about.
4. New orders and sign-ins use CentralNic Reseller automatically.

## Requirements

- A running PeltyCMS panel with WASM addons enabled
- Valid CentralNic Reseller API / OAuth / panel credentials (depending on the integration)
- Outbound HTTPS from the panel to CentralNic Reseller

## Get it

[CentralNic Reseller on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/registrar-centralnic)

Free official build. Source for this package lives in this repository.

## Support

- Marketplace product page: https://market.mythicalsystems.org/marketplace/product/registrar-centralnic
- PeltyCMS core: https://github.com/MythicalLTD/PeltyCMS
- Issues for this addon: use this repo’s Issues tab
