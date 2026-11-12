## Data Dictionary
The following are the features found in edible_plants.csv:

|variable                |class     |description                           |
|:-----------------------|:---------|:-------------------------------------|
|taxonomic_name          |character |Full taxonomic name. |
|common_name             |character |Common name. |
|cultivation             |character |Cultivation class. |
|sunlight                |character |How much sunlight the plant requires. |
|water                   |character |How much water the plant requires. |
|preferred_ph_lower      |double    |Preferred pH (lower limit). |
|preferred_ph_upper      |double    |Preferred pH (upper limit). |
|nutrients               |character |The nutrient level the plant requires. |
|soil                    |character |The type of soil the plant requires. |
|season                  |character |The season the plant grows in. |
|temperature_class       |character |The temperature class of the plant. |
|temperature_germination |character |Optimal germination temperature (Celsius). Often a range of values. |
|temperature_growing     |character |Optimal growing temperature (Celsius). |
|days_germination        |character |Days to germination at optimum temperature. Often a range of values. |
|days_harvest            |character |Days of growing to harvest. |
|nutritional_info        |character |The nutrients found in the plant. |
|energy                  |double    |Energy Value per 100g raw (Kcal). |
|sensitivities           |character |Sensitivities i.e. issues the plant might face. |
|description             |character |General description of the plant. |
|requirements            |character |Longer text description of the plant requirements. |

## Where this was found
This dataset comes from [Tidy Tuesday](https://github.com/rfordatascience/tidytuesday/tree/main/data/2026/2026-02-03):

> This week we're exploring edible plants! The Edible Plant Database (EPD) is an outcome of the GROW Observatory, a European Citizen Science project on growing food, soil moisture sensing and land monitoring. It contains information on 146 edible plant species, including their ideal growing conditions and time to harvest and germination.

> The Edible Plant Database provides data based on geographical location and growing season to answer questions such as 
"What can I plant now" and "what can I plant that will yield a crop on some future date". "Do plants that require more sunlight also require higher temperatures?" "What cultivation classes require the most water?"

## Additional background research

This is where you can add related work or other code examples of folks using your dataset (or a similar dataset).