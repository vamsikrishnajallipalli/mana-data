# ManaData (మన డేటా) - Our Data

## Open Data Platform for Andhra Pradesh

ManaData is an open-source, open-data dashboard for the people of Andhra Pradesh, designed to make public data accessible, understandable, and useful for citizens, researchers, journalists, policymakers, and technologists.

## Vision

To empower every citizen of Andhra Pradesh with **free, clean, and actionable public data**, delivered in a transparent, mobile-friendly, and bilingual (Telugu + English) format.

## Features

- **Open Data Repository**: Curated datasets from diverse domains like education, healthcare, agriculture, welfare, environment, and governance.
- **Bilingual Interface**: Complete support for Telugu and English.
- **Interactive Visualizations**: Easy-to-understand charts and graphs.
- **Mobile-First Design**: Accessible on all devices.
- **Data Download Options**: Raw data available in multiple formats.
- **API Access**: Programmatic access to all datasets.

## Getting Started

### Prerequisites
- Node.js (v18 or later)
- npm or yarn
- MongoDB (v5 or later)

### Installation

```bash
# Clone the repository
git clone https://github.com/vamsikrishnajallipalli/mana-data.git
cd mana-data

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env file with your configuration

# Start the development server
npm run dev
```

## Project Structure

- `/frontend`: React-based user interface
- `/backend`: Node.js API server
- `/data-pipeline`: Scripts for data processing and standardization
- `/datasets`: Sample and seed datasets
- `/docs`: Documentation

## Contributing

ManaData is a community-driven project under the OpenAP initiative. Contributions are welcome! Please see our [CONTRIBUTING.md](./CONTRIBUTING.md) file for guidelines.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## Acknowledgments

- [OpenAP Initiative](https://openap.org)
- All the data providers and government departments that make their data available
- The citizens of Andhra Pradesh who inspire this work
