# vpn-fleet-catalog

**Public** server list for [Cyber VPN](https://github.com/enamulhaque028/cyber-vpn).

| File | Role |
|------|------|
| `fleet/catalog.json` | Credentials + OpenVPN servers (vpnbook + VPN Gate) |
| `fleet/catalog.meta.json` | Build metadata (`sha256`, counts) |

## App fetch URLs

- jsDelivr: `https://cdn.jsdelivr.net/gh/enamulhaque028/vpn-fleet-catalog@main/fleet/catalog.json`
- Raw GitHub: `https://raw.githubusercontent.com/enamulhaque028/vpn-fleet-catalog/main/fleet/catalog.json`

Ingest / GitHub Actions live in the **private** `cyber-vpn` repo and publish here. Do not put Flutter source or VPNBOOK secrets in this repository.

Shared free-VPN credentials and `.ovpn` configs in this file are intentionally public (same class of exposure as a public CDN catalog).
