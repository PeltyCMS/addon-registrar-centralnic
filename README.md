# CentralNic Reseller

Official **PeltyCMS** `registrar` WASM addon (`registrar-centralnic`).

## Install

1. Open Pelty Admin → Addons → Marketplace
2. Set registry URL to `https://market.mythicalsystems.org/api/pelty/addons/registry.json`
3. Download **CentralNic Reseller**

Marketplace: https://market.mythicalsystems.org/marketplace/product/registrar-centralnic  
Product ID (CI): `82`

## Develop

This repository is a git submodule of [MythicalLTD/PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) at `extensions/addons/reg-centralnic`.

```bash
# from the PeltyCMS monorepo
cargo xtask addons reg-centralnic
```

## Release (Mythic Marketplace)

Same flow as [featherpanel-com/PterodactylPanelApi](https://github.com/featherpanel-com/PterodactylPanelApi):

1. Repo secrets: `MYTHIC_PRODUCT_ID`, `MYTHIC_RELEASE_TOKEN`
2. Repo variable: `ADDON_DIR=reg-centralnic`
3. Actions → **Release Addon** → Run workflow

Publishes the packed `registrar-centralnic.zip` via `MythicalLTD/.github/actions/publish-release@v1` and creates a GitHub Release.
