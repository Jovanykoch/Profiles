Backup of the deleted [DivineEngine/Profiles](https://github.com/DivineEngine/Profiles/).


# Profiles for Surge & QuantumultX

This repository contains production-ready proxy rule configurations and resources for iOS clients, primarily Surge and Quantumult X. It is designed for students and advanced users managing multiple regions, providing well-organized, regularly updated rule sets and templates for fast deployment and customization.

## Supported Platforms

- **Surge** (v5+ recommended)
- **Quantumult X**

## Quick Start

### For Surge

1. Open Surge on your iOS device, go to "Profiles."
2. Add a subscription with the following URLs:
- Outbound profile (global to overseas):  
      `https://raw.githubusercontent.com/Jovanykoch/Profiles/main/Surge/Outbound.conf`
- Inbound profile (overseas to China):  
      `https://raw.githubusercontent.com/Jovanykoch/Profiles/main/Surge/Inbound.conf`

### For Quantumult X

1. Open Quantumult X and go to "Settings" > "Profiles."
2. Add a subscription with the following URLs:
 - Outbound profile:  
      `https://raw.githubusercontent.com/Jovanykoch/Profiles/main/Quantumult/Outbound.conf`
 - Inbound profile:  
      `https://raw.githubusercontent.com/Jovanykoch/Profiles/main/Quantumult/Inbound.conf`

## Directory Structure

- `Surge/`  
  Main Surge config files, modules, rewrites, and rulesets.
    - `Outbound.conf` / `Inbound.conf` - Main config profiles
    - `Module/`        - Surge script modules
    - `Rewrite/`       - Rewrite scripts
    - `Ruleset/`       - Domain filtering rule-sets (`Netflix.list`, `China.list`, etc.)
- `Quantumult/`  
  Quantumult X configuration and rules.
    - `Outbound.conf` / `Inbound.conf` - Main config profiles
    - `Filter/`      - Filter rules
    - `Rewrite/`     - Rewrite scripts
- *Optional*:
    - `scripts/`     - Automation or linting tools for update/sync (planned)
    - `docs/`        - Extended documentation (planned)

## Maintenance & Automation

- This repository periodically syncs with upstream sources and undergoes format linting for improved stability.
- [Planned]: GitHub Actions integration for auto-updates, rule validation, and change logs.

## Contribution

- PRs and Issues are welcome if you find any problems or want to contribute region-specific rules.
- Please do NOT submit any files containing private credentials, API keys, or paid subscription URLs.

## License

MIT License

---

> Fast imports, stable production rules, supporting multi-region and Surge/Quantumult X.  
> For commercial/public or academic deployments, please read all comments in rule files before use.