# Seoul Subway Line 2 Ridership Visualization

This project visualizes yearly passenger data for Seoul Subway Line 2 from 2019 to 2024, highlighting how ridership changed during the COVID-19 pandemic. By merging station coordinates with passenger statistics, it generates an interactive map in Plotly, allowing you to explore changes in passenger volumes over time.

## Data Sources
- **Seoul Metro Passenger Data (Open License)**  
  Yearly boarding/alighting counts per station.
  <https://www.data.go.kr/data/15071921/fileData.do>
  
- **Station Coordinates Data (Excel file)**  
  Latitude and longitude for each station, mapped with English names.
<https://www.data.go.kr/data/15099316/fileData.do?recommendDataYn=Y#/layer_data_infomation>

## Features
- **Animated Map**: Use a slider to explore ridership trends by year (2019–2024).
- **Marker Size & Color**: Stations with higher passenger counts appear larger and in a deeper green color.
- **Station Short Codes**: Each station is labeled with a concise short code for quick reference.
- **Pandemic Effect**: Observe how ridership shifted during the COVID-19 period.

## How to Run
1. **Install dependencies**:
   ```bash
   pip install pandas plotly openpyxl
