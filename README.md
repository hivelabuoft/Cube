# VizCube Dataset

## Overview
The VizCube Dataset merges detailed user profiles with various data visualization types and corresponding visual analysis tasks to foster the development of intelligent, user-adaptive visualization systems. By documenting the interaction between user characteristics and visualization task performance, this dataset is uniquely positioned to drive advancements in personalized visualization tools. It is open-source and aims to support research and development in the field.

## Dataset Description
The dataset is divided into two primary components:

1. **User Test Data**: Profiles covering long-term characteristics such as personality traits and cognitive abilities of users.
2. **Analysis Tasks Data**: Interaction data of users with various visualizations as they perform specific analysis tasks, including measurements of short-term cognitive states.

### User Characteristics
Captures 9 different user characteristics through a battery of well-established psychological and HCI-related tests:
- **Locus of Control**
- **Need for Cognition**
- **Big-Five Personality Test**
- **5-Dimensional Curiosity Scale**
- **Perceptual Speed**
- **Visual Scanning**
- **Visual Disembedding**
- **Spatial Memory**

### Visualizations
The dataset includes 25 different types of visualizations, each with a shorthand code for quick reference:
- BC: Simple Bar Chart
- SB: Stacked Bar Chart
- DB: Diverging Stacked Bar Chart (with Neutral Parts)
- HS: Histogram (from binned data)
- HM: 2D Histogram Heatmap
- CS: Colored Scatterplot
- BU: Bubble Plot (Natural Disasters)
- ML: Multi-Series Line Chart
- SG: Slope Graph
- CO: Comet Chart
- AR: Area Chart
- SA: Stacked Area Chart
- HT: Annual Weather Heatmap
- LS: Lasagna Plot (Dense Time Series Heatmap)
- MS: Mosaic Chart with Labels
- RD: Radial Plot
- WF: Waterfall Chart of Monthly Profit and Loss
- PL: Parallel Coordinate Plot
- SD: Scatterplot with Mean and SD Overlay
- BP: Box-Plot with Pre-Calculated Summaries
- DP: Ranged Dot Plot
- HR: Horizon Graph
- RC: Horizontally Repeated Charts
- CH: Choropleth of Unemployment Rate per County
- OD: One Dot per Zipcode in the US

### Visual Analysis Tasks
Five categories of tasks, each with a shorthand code for referencing specific tasks related to each visualization type:
- ID: Identification Task
- C: Comparison Tasks
- T: Trend Analysis Tasks
- RC: Relationship and Correlation Tasks
- DE1: Data Exploration

Examples of task references:
- HT_ID: Identification task for the Annual Weather Heatmap.
- CS_C: Comparison task for the Colored Scatterplot.

### Short Cognitive State Measurement
After each task, a shortened test inspired by the NASA-TLX is administered to measure cognitive load, capturing changes in real-time cognitive states throughout different tasks.

## Applications
This dataset supports a variety of applications in fields such as data visualization, HCI, educational technology, and adaptive systems design. It is ideal for:
- Developing personalized visualization systems.
- Academic research into the effects of user characteristics on visualization effectiveness.
- Enhancing user experience in educational and professional settings through tailored visual presentations.

## Getting Started
1. **Clone the Repository**
2. **Explore the Datasets**
   - The User Test data is located in the file named "Part1_User_Tests.csv".
   - The Analysis Tasks data is stored in the file "Part2_Analysis_Tasks.csv".

## Authors
- Fernando Yanez
- Ella Hugie
- Carolina Nobre

## Acknowledgments
- Participants and collaborators who contributed to the dataset collection and validation.
- Funding and research support from the University of Toronto.
