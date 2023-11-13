# NISR-Hackaton competition 2023
## Gross Domestic Product and Consumer Price Index 2022

###  Consolidated Dashboard
This project explores and analyzes Gross Domestic Product (GDP) and Consumer Price Index (CPI) data for the year 2022. 
The main output is a consolidated dashboard created using RStudio's Shiny and flexdashboard.

###### Technologies Used

- RStudio
- Shiny
- flexdashboard
- tidyverse
- plotrix
- rAmCharts4
- hrbrthemes

### Dashboard Theme

The dashboard is styled with the following theme settings:

```yaml
theme:
  bg: "#101010"
  fg: "#FDF7F7" 
  primary: "#2980b9"
  base_font:
    google: Prompt
  code_font:
    google: JetBrains Mono
```
### Data Sources

The project utilizes two datasets:

1. [CPI_time_series_December_2022](https://statistics.gov.rw/publication/1914)
2. [R_GDP National Accounts 2022_r](https://statistics.gov.rw/publication/1888)

### Getting Started
1. Install required libraries by running the following R code:
install.packages(c("flexdashboard", "shiny", "tidyverse", "plotrix", "rAmCharts4", "hrbrthemes"))

2. Clone this repository.

3. Download the datasets (CPI_time_series_December_2022 and R_GDP National Accounts 2022_r) and place them in the dataset directory.

4. Run the R script consolidated_dashboard.R to generate the dashboard.

### Dashboard Structure

The dashboard is organized into sections for GDP and CPI analysis. The dataset cleaning, transformation, and building graph steps are documented in the script.


### Usage
1. Open RStudio.

2.Open the consolidated_dashboard.R script.

3.Run the script by press (Ctrl+shift+k) to generate the Shiny app and view the dashboard.

### Contributing
Contributions are welcome! Feel free to fork the repository, make improvements, and submit pull requests.




