Used Cars Price Prediction

Objective
This report deep dives into a reduced-size Kaggle dataset containing information on 426,000 used cars. Its objective is to ascertain the factors that contribute to used car pricing, using exploratory data analysis and machine learning models within the CRISP-DM framework https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining. Accurately predicting used car prices aims to deliver value to stakeholders, including car dealerships, individual sellers and buyers, and financial institutions.

Executive Summary 

Key Findings
Key features influence the price of used cars. While there is no linear relationship between the price of a used car and other features, non-linear relationships, including polynomial features of independent variables, significantly influence the target price of used cars.
These features ranked by permutation importance, include the combined impact of price and year of manufacture, followed by year of manufacture by itself. Additionally, significant factors include cylinders, combined impacts of year and cylinder, year and odometer, price and odometer, price and cylinders, fuel type (diesel and gas), specific states like Oklahoma, truck models, manufacturers such as Mitsubishi and Porsche, and transmission types (automatic and manual), particularly sedan variants.

 
Insights and Implications 
It is noteworthy that electric cars, paint colors, and a clean title status were not found to significantly influence the price of cars within the studied years between 2000 to 2020.

Interesting Findings 

Feature	Recommendation	Feature Coefficient	Impact on used Car price	Interpretation
Price and Year	Consider Pricing Strategies that consider both features comprehensively	10841.8756 (price and year combined)
3880.2149
(year only)	Positive influence 	Year of manufacture tends to increase used car price
Cylinders	Promote higher cylinder car models in the inventory as they are perceived to offer better performance with increased power 	3207.6857	Positive influence	Higher number of cylinders increases used car price
Odometer and Year	Promote models in inventory that have a lower mileage with a recent year of manufacture as they are perceived to have a longer potential lifespan	463.6157	Positive influence	Lower mileage on a relatively recent car increases its price
Fuel diesel	With better fuel efficiency, diesel cars in the inventory will attact buyers looking to save on fuel cost over the long term	3.1872	Positive influence	Higher demand for diesel cars results in higher resale price for a used car
Type Truck with drive 4wd, Convertible	Increase the inventory with trucks that offer off-road performance and convertibles with their seasonal appeal	1.9728
0.8858
Drive 4wd- 0.5652	Positive influence	Features that contribute to higher resale prices
State Ok, Ar	Research regional demand and local market before pricing cars in inventory	1.8968
0.7263	Positive influence	Regional preferences increase used car prices
Manufacturer – Mitsubhishi, Aston Martin, Porsche	With perceived reliability and lower maintenance, having branded and luxury cars in the inventory will increases sales 	1.4486
1.3874
1.1066	Positive influence	Brands that result in appreciation of used car prices
Year and Cylinders, Higher odometer mileage, Odometer and Cylinders	Older cars with lower cylinders and higher mileage tend to sell less. Consider careful pricing strategies also factoring in state/region with its demand	-3201.4618
-462.7157
-26.1842	Negative influence	Older cars with higher mileage and low cylinder count result in depreciation of used car prices
Automatic Transmission,
Fuel type of gas and hybrids, Sedan Type	Consider including these depreciating features in your pricing strategy. Offer incentives and limited time promotions can make these used cars attractive to buyers increasing sales.	-1.3445
Gas -2.5235
Hybrids -0.8815
Sedan type -1.0686	Negative influence	Features that result in depreciation of used car prices
Manufacturer – Hyundai, Nisaan	Factor in brands that decrease resale prices when pricing the inventory	-0.0027
-0.0053	Negative influence	Brands that result in depreciation of used car prices
  
Recommendations
Based on features identified as having higher importance in influencing the price of used cars, here are some recommendations.
Focus on Pricing Strategy: Given the strong influence of price and year of manufacture together, optimize pricing strategies that consider both factors comprehensively.
Highlight Year of Manufacture: Emphasize the year of manufacture prominently in vehicle listings and marketing materials, as it significantly impacts pricing.
Manage Mileage: Since odometer (mileage) is influential, prioritize vehicles with lower mileage or provide transparency and justification for higher mileage vehicles.
Consider Fuel Efficiency: Given the impact of fuel type (diesel and gas), consider promoting vehicles with fuel-efficient technologies or highlighting their cost-effectiveness.
Regional Considerations: Recognize the influence of specific states like Oklahoma and tailor marketing or pricing strategies accordingly for regional markets.
Model and Transmission Preferences: Cater to preferences for specific truck types, manufacturers like Mitsubishi and Porsche, and transmission types (automatic and manual) by ensuring a diverse inventory that meets varied customer preferences.
Continue reading for an in-depth analysis of the model evaluation that underpins the findings and recommendations discussed.

