# Data Analysis on Renewable Energy

My team and I were to give a project where we must conduct a full data analyis using Data Renewable Energy 

### Mitigation: Renewable Energy

Electricity generation and electricity installed capacity, classified by energy type (renewable and non-renewable) and 10 technology types.

The data has been sourced from the [International Renewable Energy Agency](https://pxweb.irena.org/pxweb/en/IRENASTAT).

The indicators on energy transition have been formulated to help users understand the progress in the adoption of renewable energy sources vis-à-vis the increasing energy requirements.

Sources: International Renewable Energy Agency (IRENA) (2022), Renewable Energy Statistics 2022, https://pxweb.irena.org/pxweb/en/IRENASTAT. Accessed on 2022-09-28; IMF Staff Calculations.


### Data Dictionary

| Column        | Description                                                                                      |
|---------------|--------------------------------------------------------------------------------------------------|
| ObjectId      | A unique identifier for each row in the dataset.                                                   |
| Country       | The name of the country to which the data corresponds.                                            |
| ISO2          | The two-letter country code (ISO 3166-1 alpha-2).                                                 |
| ISO3          | The three-letter country code (ISO 3166-1 alpha-3).                                               |
| Indicator     | Describes the type of indicator, such as "Electricity Generation" or "Electricity Installed Capacity." |
| Technology    | Specifies the type of technology used for electricity generation or installed capacity (e.g., Bioenergy, Fossil fuels, Geothermal energy). |
| Energy_Type   | Indicates whether the energy source is renewable or non-renewable.                                |
| Unit          | The unit of measurement for the data in the corresponding columns (e.g., Gigawatt-hours (GWh) for electricity generation, Megawatts (MW) for installed capacity). |
| Source        | Identifies the source of the data, in this case, the International Renewable Energy Agency (IRENA). |
| CTS_Name      | The name associated with the Common Tabulation Structure (CTS) for the data.                        |
| F2013 - F2022 | Columns representing the numerical data for each respective year from 2013 to 2022. These values contain information related to electricity generation or installed capacity, depending on the indicator and unit of measurement. |


credit to my team: Fikri, Farhan
