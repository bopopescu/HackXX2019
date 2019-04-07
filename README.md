We identified that one of the problems iTradeChallenge faces while inspecting 
their food shipments is the inefficiency at labeling the foods that doesn't fit 
in a specific category.
When that happens, inspector has to manually enter the food's specification, 
which usually takes a long time, and can result in confusing data.

Therefore, we came out with our Food Identification Project which takes in an 
image url under Google Cloud Storage and provides the most common web 
identification result for that image.

Our project uses Java for the main user interface and Python to integrate 
Google Cloud Vision API to obtain the identification result. 
 