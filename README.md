# Meme Analysis Project

A comprehensive analysis of meme templates and their usage across social media platforms (Reddit and Bluesky).

## Overview

This project collects and analyzes meme data from multiple social media sources to identify trends in meme template popularity, usage patterns, and temporal dynamics. The analysis includes data collection, processing, template identification, and visualization.

## Project Structure

```
meme-analysis-project/
├── data/
│   ├── raw/                          # Raw, unprocessed data from sources
│   │   ├── reddit_memes_raw.csv
│   │   └── bluesky_memes_raw.csv
│   ├── processed/                    # Cleaned and processed datasets
│   │   ├── reddit_with_templates.csv
│   │   ├── bluesky_with_templates.csv
│   │   ├── reddit_monthly_template_summary.csv
│   │   └── bluesky_monthly_template_summary.csv
│   └── miscellaneous/                # Additional datasets and analysis files
│       └── [Various meme template datasets]
├── images/
│   ├── reddit_images/                # Meme images from Reddit
│   ├── bluesky_images/               # Meme images from Bluesky
│   └── plots/                        # Generated visualizations
├── meme_project_outline.ipynb         # Main analysis notebook
└── README.md                          # This file
```

## Data Sources

- **Reddit**: PRAW (Python Reddit API Wrapper)
- **Bluesky**: Bluesky API

### Meme Templates Analyzed

- Drake (Hotline Bling)
- Distracted Boyfriend
- Expanding Brain
- Woman Yelling at Cat
- Surprised Pikachu
- Mocking SpongeBob
- Two Button Choice
- This Is Fine
- Change My Mind
- Is This a Pigeon?

## Installation & Setup

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd meme-analysis-project
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
   Required packages: pandas, numpy, matplotlib, seaborn, jupyter

3. **Jupyter notebook**
   ```bash
   jupyter notebook meme_project_outline.ipynb: Main analysis notebook containing data exploration, visualization, and statistical analysis
   ```

## Analysis Highlights

- **Dataset Overview**: Reddit (858 posts, ~747 avg likes) vs Bluesky (2946 posts, ~428 avg likes) with Reddit spanning a longer timeframe
- **Platform Dynamics**: Bluesky driven by community reuse; Reddit characterized by short, high-intensity viral bursts
- **Cross-Platform Differences**: Meme popularity is platform-specific; Reddit shows concentrated engagement while Bluesky is more evenly distributed
- **Clustering & Embeddings**: Meme templates do not form clear visual clusters; platform effects significantly influence meme structure and meaning
- **Limitations**: Analysis restricted to popular templates; API constraints and survivorship bias affect data completeness; engagement metrics simplified (likes/replies)

## Contributing

Feel free to submit issues or pull requests to improve the analysis or add new features.

## License

This is an academic project created for educational purposes. Use is restricted to educational and non-commercial purposes.