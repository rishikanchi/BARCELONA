# BARCELONA: Boosting Accessibility and Rideshare Convenience through Efficient Local Operations in Non-optimal Areas

<a id="readme-top"></a>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#research-paper">Research Paper</a></li>
    <li><a href="#results-and-findings">Results and Findings</a></li>
    <li><a href="#data-visualizations">Data Visualizations</a></li>
    <li><a href="#methodology">Methodology</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

**BARCELONA** is a data-driven research project that explores how Uber can strategically partner with hotels in Barcelona to expand its market share and compete with the city's extensive public transportation network. This study was developed for the **Uber Global Hackathon - Data Analysis Track** by the **Fremd Team**.

### 🎯 Research Objective

Barcelona's heavy investment in public transportation (buses, underground, railways, etc.) currently dominates the transportation market with over 1 billion trips annually. However, with recent EU court rulings overturning restrictive regulations, Uber now has access to Barcelona's lucrative tourism market of 12 million annual visitors.

This study proposes a **hotel partnership strategy** where Uber offers discounted rates to hotel guests as a "foot-in-the-door" technique to gain market share among tourists who may prefer ride-hailing over public transportation due to language barriers or convenience.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- RESEARCH PAPER -->

## Research Paper

📚 **[Read the Full Research Paper](BARCELONA_Research_Paper.pdf)**

The comprehensive research paper contains detailed analysis of Barcelona's transportation landscape, Uber's market entry strategy, and data-driven insights for hotel partnerships.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- RESULTS AND FINDINGS -->

## Results and Findings

### 🎯 Key Findings

- **Optimal District**: Eixample identified as most favorable (travel coefficient: 200+)
- **Target Hotels**: 5 hotels with highest partnership potential
- **Efficiency Advantage**: 91% of trips faster by car than public transportation
- **Revenue Potential**: €5,571,360+ annual revenue from hotel partnerships

### 📊 Quantitative Results

| Metric                        | Value                   |
| ----------------------------- | ----------------------- |
| Travel Coefficient (Eixample) | 200+                    |
| Driving Efficiency            | 91% faster than transit |
| Annual Uber Trips             | 464,280+                |
| Projected Revenue             | €5,571,360+             |
| Optimal Discount              | 50% (3 uses per family) |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- DATA VISUALIZATIONS -->

## Data Visualizations

### 🗺️ Transportation Concentration Heatmap

![Transportation Heatmap](images/district_bus_concentrations.png)

_Visual representation of transportation stop density across Barcelona districts. Lighter shades indicate lower concentration, darker shades indicate higher concentration._

### 🏨 Eixample Hotel Analysis

![Eixample Hotels](images/eixample_transportation_coordinates.png)

_Geospatial analysis of hotels in Eixample district. Red stars indicate the 5 target hotels identified for Uber partnerships._

### 🚗 Driving Efficiency Analysis

![Driving Efficiency](images/hotel_driving_efficiency.png)

_Comparison of driving vs. public transportation efficiency. Green indicates higher driving efficiency, red indicates lower efficiency._

### ⏱️ Transportation Mode Comparison

![Transportation Comparison](images/travel_totals.png)

_Pie chart showing that 91% of trips from target hotels to major attractions are faster by car than public transportation._

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- METHODOLOGY -->

## Methodology

### 🛠️ Built With

This project leverages a powerful technology stack combining data analysis with geospatial visualization:

#### Data Analysis Tools

- [Pandas](https://pandas.pydata.org/) - Data manipulation and analysis
- [NumPy](https://numpy.org/) - Numerical computing
- [Seaborn](https://seaborn.pydata.org/) - Statistical data visualization
- [Matplotlib](https://matplotlib.org/) - Plotting library

#### Geospatial Analysis

- [Folium](https://python-visualization.github.io/folium/) - Interactive maps
- [Geopy](https://geopy.readthedocs.io/) - Geocoding services

#### Development Environment

- [Jupyter Notebook](https://jupyter.org/) - Interactive computing
- [Python 3.8+](https://www.python.org/) - Programming language

### 📁 Datasets Used

The project utilizes comprehensive Barcelona datasets from 2017:

- **Population Data**: Neighborhood population statistics
- **Unemployment Data**: Employment rates by district
- **Immigration Data**: Movement patterns between districts
- **Transportation Data**: Locations of all public transport stops
- **Bus Stop Data**: Detailed bus stop locations
- **Hotel Data**: Geolocations of 31 Eixample hotels

### 📊 Data Analysis Process

```
User Query → Travel Coefficient Calculation → District Selection → Hotel Analysis
                      ↓
              Efficiency Comparison → Target Identification → Revenue Projection
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

### 📥 Installation

To reproduce the analysis:

```bash
# Clone the repository
git clone https://github.com/rishikanchi/FremdUGH.git
cd BARCELONA

# Install required dependencies
pip install pandas numpy seaborn matplotlib gmaps googlemaps geopy folium jupyter

# Launch Jupyter Notebook
jupyter notebook

# Open and run the analysis notebooks
```

### 🔧 Prerequisites

- Python 3.8+
- Jupyter Notebook
- Google Maps API key (for geospatial analysis)
- Basic understanding of data analysis and visualization

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [x] District analysis and selection
- [x] Hotel efficiency evaluation
- [x] Target hotel identification
- [x] Revenue projection modeling
- [x] Research paper publication
- [ ] Real-time data integration
- [ ] Expanded hotel partnerships
- [ ] Multi-city analysis framework
- [ ] Dynamic pricing algorithm
- [ ] Mobile application interface

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the terms specified in `datasets/license.md`.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

**Rishi Kanchi** - rishirkanchi@gmail.com

**Project Repository**: https://github.com/rishikanchi/FremdUGH

**Team Members**:

- Mithun Arun (mithuna1389@gmail.com)
- Ryan Barretto (ryanbarretto70@gmail.com)
- Andrew Qian (andrewyukaiqian@gmail.com)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

> "Barcelona's transportation challenge is Uber's opportunity. Through strategic hotel partnerships and data-driven insights, we can create a win-win scenario for tourists, hotels, and ride-sharing services."
> — **Fremd Team**

[![Uber Global Hackathon][Uber-badge]][Uber-url]

<!-- MARKDOWN LINKS & IMAGES -->

[Uber-badge]: https://img.shields.io/badge/Uber_Global_Hackathon-000000?style=for-the-badge&logo=uber&logoColor=white
[Uber-url]: https://www.uber.com/
