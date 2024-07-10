# EcoGrow Advisor: Weighted, Regression Model-based Recommender System
EcoGrow Advisor is a model designed for sustainable planting, providing tailored recommendations for tree planting based on geographic data, optimizing land use, and calculating potential Green Credits.

## Data
Synthetic Dataset generated with 100 datapoints with the following parameters:

1. Land Parcel ID
2. State
3. District
4. Division
5. Latitude
6. Longitude
7. Land Area (hectare)
8. Soil Type
9. Soil pH
10. Avg Temperature (°C)
11. Avg Rainfall (mm/year)
12. Humidity (%)
13. Slope
14. Elevation (meters)
15. Proximity to Water
16. Water Availability
17. Native Species
18. Carbon Sequestration (kg CO2/year/tree)
19. Maintenance Requirements
20. Growth Period (Months)
21. Cost (per hectare)
22. Planting Density (trees per hectare)

## Factors (UI Filters)

1. **Growth Period (in Months)**: Input options: 24, 36, 48, 60, 72 (drop-down)
2. **Land Area (in hectare)**: Values between 5-30
3. **Green Credit**: Continuous values
4. **State**: Input options: Karnataka, Maharashtra, Uttar Pradesh, Gujarat, Tamil Nadu (drop-down)
5. **Cost (per hectare)**: Values between 1000 and 5000
6. **Tree Specie(s)**: Input options: Neem, Banyan, Teak, Bamboo, Sandalwood, Rosewood, Mango, Tamarind, Sal, Pine, Oak, Mahogany, Eucalyptus, Pine (drop-down)

## Output

Top 10 Recommendations:

- **Land Parcel ID**:
- **Tree Specie(s)**:
- **Land Area (in hectare)**:
- **State**:
- **District**:
- **Division**:
- **Latitude and Longitude**:
- **Growth Period**:
- **Total Cost Estimate (in Rupees)**:
- **Green Credit Earnings Estimate**:
- **Carbon Credit Earnings Estimate**:
- **Maintenance Requirements**:

## To Install the Requirements, run the below command on the terminal :

**pip install -r requirements.txt** 

