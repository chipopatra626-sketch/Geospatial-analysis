# Geospatial-analysis
Geospatial analysis in Excel using simulated data: mapping online orders across Zambian towns to find where to open new shops
# Geospatial Data Analysis: Where Should the Next Shop Open?

Simulated dataset of online orders from 20 Zambian towns, created for practice with AI assistance.

## Goal
Find towns with high demand but no shop, and map sales by location to suggest where the business could expand.

## Key metrics
- Total online orders: 3,250
- Total shops: 10
- Average orders per shop: 167
- Orders from towns with no shop: 1,580 (48.6%)

## Key findings
- Nearly half of all orders come from towns without a shop.
- Four towns have no shop but 150 or more orders: Solwezi (260), Chingola (210), Kasama (175) and Mazabuka (155). Together they brought in K160,475, about 25% of all sales.
- Solwezi has more orders (260) than any single existing shop handles, including each Lusaka shop (about 203).
- Kasama is far from any existing shop, and Northern Province has no shop.
- Chingola is close to Kitwe, which has 2 shops, so some of its customers may already be served there.
- Copperbelt Province has the most orders (1,160) and 4 of the 10 shops.

## Recommendations to test
- Consider Solwezi first for a new shop, because its demand is highest.
- Consider Kasama next, to reach customers in the north.
- Before opening in Chingola or Mazabuka, test cheaper options, such as a pickup point or faster delivery from Kitwe or Lusaka.

## The map
zambia_orders_map.png shows each town by its approximate location. Bubble size shows online orders. Orange labels mark opportunity towns, and green labels mark towns with shops. Lusaka, Ndola and Kabwe have shops but are not coloured because their bubbles overlap with nearby towns.

## Limitations
- The data is simulated and small, so results are for practice only.
- Online orders show existing demand, not everyone who might buy from a shop.
- Town locations are approximate, and travel distances were not measured.
- Shop costs, rent and competition were not included.

## Files
- zambia_sales_locations.csv: original data
- Geospatial-Analysis.xlsx: calculations and map
- zambia_orders_map.png: map image
