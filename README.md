# Identifying shopping centers with high operating loss risk and potential redevelopment opportunities

Chi Zhang, Candiadte MUSA 2022
## Background
At present, number of shopping centers opened or to be opened in Shanghai will be as high as 419. For 2020, The area of shopping centers per person is 0.97m2. Both count and area of malls are dramatically increasing since 2009. Considering the climbing vacancy from 2019 to recent, the retail market in Shanghai is oversupplied, which follows with the high operating loss risk and value mismatch of location and operation.
## Goals & Values
- Finding out shopping centers with operating loss risk with gravity model and real estate finance formulas. The results are tested with social media data.
- Analyzing mismatch of operation and location value with entropy weight method and regression model
For the researcher, this paper explores a creative application of gravity model and fills a research gap in quantifying operating loss risks. For the government, the quantified results can be considered as an influence factor before implementation of land use planning and urban regeneration.

This research aims to use econometric model to validate if shopping center overbuilt exists in Shanghai. For the over-developed districts, a regression model is built to identify surplus shopping centers with investment potential for future regeneration or redevelopment.
## Folders
- See `/raw_data` for identified datasets:
  - ShoppingCenter(age/area/coordinates/customer gradings)
  - Census(population/disposable income/consumption expense)
  - UrbanEvironment(public transit stations/roads/parks/POI)
  - GeoData(geodatabase of Arcmap file)
- See `/model` for scripts and Arcmap file.
  - Notebook of data cleaning and exploration
  - Arcmap of gravity model
  - Spreadsheet of financial calculation
