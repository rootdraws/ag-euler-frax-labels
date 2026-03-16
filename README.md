# ag-euler-frax-labels

Labels repo for the Frax ICHI Vault cluster on Base (8453).

Push to `rootdraws/ag-euler-frax-labels` on GitHub. The frontend fetches these files from raw GitHub URLs.

## Post-Deployment

After running the 7 deployment scripts in `frax-contracts/script/`, update the placeholder addresses in:

- `8453/products.json` — Replace `REPLACE_WITH_*` with actual eVault addresses from `.env`
- `8453/vaults.json` — Same replacements (keys must be checksum addresses)

## Logos

Add SVG/PNG logos to `logo/`:
- `alphagrowth.svg` (copy from existing labels repo)
- `frax.svg`
- `ichi.svg`
- `hydrex.svg`
- `euler.svg`
