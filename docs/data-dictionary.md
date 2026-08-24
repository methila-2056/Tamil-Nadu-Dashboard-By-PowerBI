# Data Dictionary — `TN_Districts_Data.csv`

Reference for the district-level dataset visualized in the Power BI dashboard.

| Column | Type | Description |
|--------|------|-------------|
| `District_Name` | Text | District name in English |
| `District_Tamil` | Text | District name in Tamil |
| `Population` | Integer | Total population of the district |
| `Male_Population` | Integer | Male population |
| `Female_Population` | Integer | Female population |
| `Literacy_Rate` | Decimal | Literacy rate (%) |
| `Sex_Ratio` | Integer | Females per 1,000 males |
| `Area_SqKm` | Decimal | Geographic area in square kilometers |
| `Density` | Decimal | Population density (persons per sq km) |
| `Urban_Percent` | Decimal | Share of urban population (%) |
| `Rural_Percent` | Decimal | Share of rural population (%) |
| `Region` | Text | Zone/region grouping used for slicing visuals |

## Usage Notes

- Use `Region` as a slicer field to compare zones such as North, South, East, West and Delta districts.
- `Density` is pre-computed; recompute only if you replace the source data.
- Percent fields are stored as whole numbers (0–100); format them as percentages in DAX measures if needed.
