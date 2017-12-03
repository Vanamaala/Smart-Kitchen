# Smart-Kitchen
Digital cooking experience

SCOPE

Automated User & Ingredient/item identification, Food ingredients Inventory management, Healthy Recipe recommendation & Cooking Guidance, Automation assisted cooking
 

USECASE
 
Premise

·         Entire Food items & ingredients inventory are stored in a climate controlled refrigeration system (lets call it FOODSTORE) – System has compartments for Heat, Warm, Room Temp, Cold, Frozen etc
·         FOODSTORE has capability to auto order items as they deplete based on user preference/settings etc
·         All food containers are all bar coded for identification of container properties and its contents
·         Cooking containers are used for cooking purposes and are barcoded as well. They are stored in a Cooking container storage unit
·         Non-Perishables and packeted Food items are bar coded where possible. Perishables and other items rely on visual sensors on the kitchen, fridge etc to identify them
·         Kitchen console(lets call it CONSOLE)  is an interactive system that engages the user and also coordinates with all other systems to manage the cooking experience
 

User Actions

SELECTION OF RECIPE

·         User enters the kitchen
·         CONSOLE uses visual sensors to identify user and greets the user and gives some recipe recommendations based on ingredients available, time of the day, user’s preference, special occasion, new trends etc
·         User can pick from recommendation or select specific recipe
·         CONSOLE also provides green, healthy recipe alternative for selected recipe
·         When user picks a recipe CONSOLE verifies inventory by invoking services exposed by FOODSTORE. If Inventory shortage is forseen, Console recommends alternative ingredients


ACTION OF COOKING

·         CONSOLE guides user on what to pick, where to pick, which food container to pick, cooking container to pick etc – CONSOLE invokes services in FOODSTORE to provide this info
·         User selects cooking containers from the shelves and food containers with ingredients from the FOODSTORE
·         Visual sensors and Bar code sensors identify and monitor containers used and ingredients selected  – CONSOLE invokes services in VISUAL AND BARCODE SCANNERS in OVERHEAD SCANNER & FOODSTORE to provide this info
·         CONSOLE guides user on what to do based on ingredient selected
·         CONSOLE feeds recipe, container and food data info to the GASRANGE and MICROWAVE
·         User typically performs a step by step cooking process by incrementally adding ingredients
·         MICROWAVE & GASRANGE periodically invokes CONSOLE to identify what ingredients are currently placed in the cooking containers(This is needed for incremental preparation) to auto cook to perfection using recipe guidelines
·         GASRANGE and MICROWAVE monitors preparation and alerts user based on temperature, timing readings. These devices can auto manage the cooking temperature as well


FINALIZATION

·         Once cooking is complete, CONSOLE recommends serving suggestions, provides calorific value, storage/freezing guidelines
·         CONSOLE requests user feedback after meal to record and improve
