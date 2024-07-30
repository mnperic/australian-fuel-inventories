# Forecasting Australian Automotive Fuel Inventories
 Using prophet to predict and forecast future Australian automotive fuel sales, imports, production, exports, and inventory levels.

 ## Overview
The premise of this project was to analyse past Australian automotive fuel sales, imports, production, exports, and inventory levels and create a predictive model to forecast future outlooks.

To conduct this, historical Australian automotive fuel data was obtained for the 2010-2023 period, and future prices were forecasted from 2024-2029.

Note: data for the total 'Inventory' of fuel was not originally provided in dataset. To calculate this variable, cumulative total was calculated, where:

<i>Production</i> for the first datetime (1/07/2010) was calculated as base
<br></br>
<i>Import</i> for the first datetime (1/07/2010) was added
<br></br>
<i>Sale</i> for the first datetime (1/07/2010) was minused, and
<br></br>
<i>Export</i> for the first datetime (1/07/2010) was minused.

## Visualisation
### Forecast
#### Sale

 <p align="center">
  <img src="https://github.com/mnperic/australian-fuel-inventories/blob/main/images/model_sale.png" alt="model"/>
</p>

#### Import

 <p align="center">
  <img src="https://github.com/mnperic/australian-fuel-inventories/blob/main/images/model_import.png" alt="model"/>
</p>

#### Production

 <p align="center">
  <img src="https://github.com/mnperic/australian-fuel-inventories/blob/main/images/model_production.png" alt="model"/>
</p>

#### Export

 <p align="center">
  <img src="https://github.com/mnperic/australian-fuel-inventories/blob/main/images/model_export.png" alt="model"/>
</p>

#### Inventory

 <p align="center">
  <img src="https://github.com/mnperic/australian-fuel-inventories/blob/main/images/model_inventory.png" alt="model"/>
</p>
