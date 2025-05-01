# Asian Open Source Communities Database

An interactive database showcasing open source communities across Asia. This project aims to connect and highlight the vibrant open source ecosystem in the Asian region.

## Project Structure

```
.
├── _quarto.yml          # Quarto website configuration
├── index.qmd            # Main landing page
├── communities/         # Individual community pages
├── data/               # Data files
│   └── communities.csv  # Main database
├── styles/             # Custom styling
└── CONTRIBUTING.md     # Contribution guidelines
```

## Adding a New Community

To add a new community to the database, you have two options:

### Option 1: Create a GitHub Issue
1. Go to the Issues tab
2. Click "New Issue"
3. Use the "Community Submission" template
4. Fill in the required information:
   - Community Name
   - Description
   - Website
   - Region
   - Category

### Option 2: Submit a Pull Request
1. Fork the repository
2. Add your community data to `data/communities.csv`
3. Create a pull request with your changes

## Data Format

Communities are stored in CSV format with the following structure:

```csv
name,description,website,region,category,country,city_state,member_count,status,type
```

## Development

This project uses:
- Quarto for website generation
- GitHub Pages for hosting
- CSV for data storage

To run locally:
1. Install Quarto: https://quarto.org/docs/get-started/
2. Clone this repository
3. Run `quarto preview` to view the site locally

## License

This project is open source and available under the MIT License. 
