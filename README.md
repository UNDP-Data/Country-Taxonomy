# Country-Taxonomy

This repo has the Country Taxonomy which is used in Data Futures Platform (https://data.undp.org/). Each country is defined as a single object in the array. The data structure is:

## Data Structure of an object

Key | DataType | Description
--- | --- | --- 
Alpha-3 code-1 | `string` | Three-letter country codes defined in ISO 3166-1
Country or Area | `string` | Name of the country or region
Alpha-2 code | `string` | Two-letter country codes defined in ISO 3166-1
Numeric code | `string` | Three-digit country codes defined in ISO 3166-1
Latitude (average) | `string` | Latitude value of the middle point of the country shape
Longitude (average) | `string` | Longitude value of the middle point of the country shape
Group 1 | `string` | The contitent area the region belong to. Available values: `Africa`, `Americas`, `Asia`, `Europe`, `Oceania`
Group 2 | `string` | 2nd level the region belongs to. Available values: `Latin America and the Caribbean`, `Northern America`, `Southern Asia`, `Central Asia`, `South-eastern Asia`, `Eastern Asia`, `Western Asia`, `Sub-Saharan Africa`, `Northern Africa`, `Southern Europe`, `Western Europe`, `Northern Europe`, `Polynesia`, `Melanesia`, `Micronesia`, `Australia and New Zealand`
Group 3 | `string` | 3rd level the region belong to.
LDC | `boolean` | Defined if a region or country belongs to Least Developed Countries (LDC) group
LLDC | `boolean` | Defined if a region or country belongs to Landlocked developing countries (LLDC) group
SIDS | `boolean` | Defined if a region or country belongs to Small Island Developing States (SIDS)
Development classification | `string`| 
Income group |`string` | Available values: `Low income`, `Lower middle income`, `Upper middle income`, `High income`

__Example__

```
{
  "Alpha-3 code-1": `string`,
  "Country or Area": `string`,
  "Alpha-2 code": `string`,
  "Numeric code": `string`,
  "Latitude (average)": `string`,
  "Longitude (average)": `string`,
  "Group 1": "Africa",
  "Group 2": "Sub-Saharan Africa",
  "Group 3": "Western Africa",
  "LDC": `boolean`,
  "LLDC": `boolean`,
  "SIDS": `boolean`,
  "Development classification": `string`,
  "Income group": `"Low income" | "Lower middle income" | "Upper middle income" | "High income" | ""`
}
```
