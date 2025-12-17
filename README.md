<p align="center">
  <a href="https://www.energyweb.org" target="blank"><img src="./images/EW.png" width="120" alt="Energy Web Foundation Logo" /></a>
</p>

# Battery Passport VC Schema

## Description

Battery Passport VC Schema provides Verifiable Credential schemas for Battery Passport data as per Battery Regulation requirements. This repository contains JSON Schema and JSON-LD context definitions for all required battery passport attributes organized into seven categories.

## Schema Overview

The repository contains schemas for the following categories:

| Category                                        |   Number of Attributes |
|:------------------------------------------------|-----------------------:|
| Battery carbon footprint                        |                      9 |
| Battery materials and composition               |                      5 |
| Circularity and resource efficiency             |                     16 |
| Identifiers and product data                    |                     11 |
| Performance and durability                      |                     42 |
| Supply chain due diligence                      |                      3 |
| Symbols, labels and documentation of conformity |                      7 |
| Total                                           |                     93 |

## Schema Categories

- **BatteryCarbonFootprint** - Carbon footprint attributes and lifecycle stage contributions
- **BatteryMaterialsAndComposition** - Material composition and sourcing information
- **CircularityAndResourceEfficiency** - Recycling and circularity metrics
- **IdentifiersAndProductData** - Product identifiers and basic product information
- **PerformanceAndDurability** - Performance characteristics and durability metrics
- **SupplyChainDueDiligence** - Supply chain transparency and due diligence data
- **SymbolsLabelsAndDocumentationOfConformity** - Compliance documentation and labeling

Each category contains:

- `{CategoryName}.json` - JSON Schema definition
- `{CategoryName}.jsonld` - JSON-LD context definition

## Documentation

- [ReadTheDocs](https://origins.readthedocs.io/en/latest/)

## Contributing Guidelines

See [contributing.md](./contributing.md)

## Questions and Support

For questions and support please use Energy Web's [Discord channel](https://discord.com/channels/706103009205288990/843970822254362664)

# EW-DOS

The Energy Web Decentralized Operating System is a blockchain-based, multi-layer digital infrastructure.

The purpose of EW-DOS is to develop and deploy an open and decentralized digital operating system for the energy sector in support of a low-carbon, customer-centric energy future.

We develop blockchain technology, full-stack applications and middleware packages that facilitate participation of Distributed Energy Resources on the grid and create open market places for transparent and efficient renewable energy trading.

- To learn about more about the EW-DOS tech stack, see our [documentation](https://app.gitbook.com/@energy-web-foundation/s/energy-web/).

- For an overview of the energy-sector challenges our use cases address, go [here](https://app.gitbook.com/@energy-web-foundation/s/energy-web/our-mission).

For a deep-dive into the motivation and methodology behind our technical solutions, we encourage you to read our White Papers:

- [Energy Web White Paper on Vision and Purpose](https://www.energyweb.org/reports/EWDOS-Vision-Purpose/)
- [Energy Web  White Paper on Technology Detail](https://www.energyweb.org/wp-content/uploads/2020/06/EnergyWeb-EWDOS-PART2-TechnologyDetail-202006-vFinal.pdf)

## Connect with Energy Web

- [Twitter](https://twitter.com/energywebx)
- [Discord](https://discord.com/channels/706103009205288990/843970822254362664)
- [Telegram](https://t.me/energyweb)

## License

This project is licensed under the GNU General Public License v3.0 or later - see the [LICENSE](LICENSE) file for details
