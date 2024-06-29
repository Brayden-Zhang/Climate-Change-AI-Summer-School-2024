
## Case Study: trip demand forecasting
* You are a data scientist at a ride-sharing company. You are tasked with building a **demand forecasting model** that, given a specific time and location, predicts the number of trips that will be requested in the next hour. 

* The proposed approach should include:
1. Metrics for trip demand
2. Features to use as predictors
3. Forecasting methods
4. Real-world testing and implementation plan
5. Discussion of general climate-relevance trip demand forecasting


### Metrics for Trip Demand
- internal data: trips searched for in the ride-hailing app
- public data: public taxi trips, public transportation ridership, weather data, events data, etc.
- Construcitng the outcome variable / metric: aggregrating the origin points of all trips searched for in the ride-hailing app


*There is too much reliance on road transporation --> too much reliance on combustion engines --> too much greenhouse gas emissions.*


### ML Use Cases
#### Urban Data
- urban data lakes --> "smart cities"
- urban open data (OpenStreetMap, etc.)

Features to use as predictors:
- weather, time-of-day, points-of-interest, location data
- Methods: could be regression or classification problem


List:
* Reducing Transportation activity
  * analyzind data
  * remote sensing
  * forecasting
  * freight consolidation
  * alternatives to traditional transportation
* Modal Shift
  * consumer choices
  * coordinating modes
  * bike share rebalancing
  * predictive maintenance
  * enforcing regulation
* Vehicle efficiency 
  * autonomous vehicles
  * fuel efficiency
  * charging scheduling
  * congestion management
  * vehicle-to-grid algorithms
  * battery energy management
    * battery R&D


Optimization
* optimization of vehicle / customer matching
* charging pattern optimization
* shared vehicle rebalancing (city bikes)

Computer vision:
* trajector  forecasting
* object detection/segmentation
* 3D vision
  * point cloud processing and analysis for autonomous vehicles
* remote sensing
  * for urban change detection

Reinforcement Learning
* traffic and congestion modeling
* agnt-based simultions for digital wins of cities

Inference:
* large-scale urban experiemnts
* causal Ml for cities

prediction:
* travel demand prediction
* load forecasting
* travel time estimation


Examples:
* transfer learning urban mobility demand
  * *Objective*: train a mobility demand forecasting model on city A and deploy it in city B to help car sharing operators
  * method: tree-based regression models
* City-scale causal discovery under network effects
  * *Objective*: discover causal relationships of a new feaure on ride-hailing trips
* More:
  * Graph NNs and scalable Gaussian Processes for modeling spatial and temporal efffects in cities at scale
  * constraint-focused methods for decision, control, and planning
  * explainable and causal ML for improving and scaling experimens
  * Multi-modal DL for harmonizing different urban data types
  * large agent-based simulations for digital twins 