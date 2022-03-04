# Flight Cancellation Prediction

### Executive Summary
This project was completed in December 2021 as a final project for Predictive Analytics course at the University of Edinburgh (Mark = 78/100 (A)). A sample of 1,936,758 records of the United States flight data in 2008 was observed to develop a predictive model on a flight cancellation problem. Several classification algorithms were applied to examine the best and most realistic model to predict a flight cancellation problem with severe class imbalance, including Logistics Regression, Decision Tree, Random Forest, Ada Boosting, and Gradient Boosting. Models were evaluated primarily using ROC-AUC and accuracy rate. The results suggested Gradient Boosting showed the highest AUC score (0.76) and the highest accuracy at 75.52%. Therefore, we can conclude that Gradient Boosting is the best classification algorithm to predict this particular problem. The result of this study enables airport operators and airline companies to mitigate the occurrences of cancellations as soon as possible, hence minimizing the potential damages, both on the service providers and the passengers.

### Data Dictionary
| Field  | Description |
| ------------- | ------------- |
| Year | Year of the flight |
| Month | Month of the flight |
| DayofMonth | Date of the flight |
| DayofWeek | Day of week of the flight |
| DepTime | Actual departure time |
| ArrTime | Actual arrival time |
| CRSArrTime | Scheduled arrival time |
| UniqueCarrier | Airlines unique code |
| FlightNum | Flight number |
| TailNum | Aircraft registration no. |
| ActualElapsedTime | Actual elapsed time of the flight in minutes (TaxiOut + AirTime + TaxiIn) |
| CRSElapsedTime | System elapsed time of the flight in minutes (TaxiOut + AirTime + TaxiIn) |
| AirTime | The time from the moment an aircraft leaves the surface until it comes into contact with the surface at the next point of landing |
| ArrDelay | Difference in minutes between scheduled and actual arrival time. Early arrivals show negative numbers, in minutes. |
| DepDelay | Difference in minutes between scheduled and actual departure time. Early departures show negative numbers, in minutes |
| Origin | IATA airport code of the flight origin |
| Dest | IATA airport code of the flight destination |
| Distance | Distance between origin and destination |
| TaxiIn | The time elapsed between the wheels down and the aircraft arrives at the destination |
| TaxiOut | The time elapsed between departure from the origin airport gate and wheels off |
| Cancelled | 1: Cancelled, 0: Otherwise |
| CancellationCode | Cancellation reasons, A = Carrier, B = Weather, C = NAS, D = Security |
| Diverted | 1: Yes, 0: Otherwise |
| CarrierDelay | Delay caused by airlines, in minutes |
| WeatherDelay | Delay caused by the weather, in minutes |
| NASDelay | Delay caused by National Aviation System (NAS), in minutes |
| SecurityDelay | Delay due to security, in minutes |
| LateAircraftDelay | Delay caused by late aircraft, in minutes |


##### Author: © Hutami Nadya Larasati 2021
