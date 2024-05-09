# Future Boundingbox Prediction 
We perform basic occupancy forecasting from ground-truth bounding box with the below two approaches. Then compare them with some metrics such as IOU and L2 distance between prediction and ground-truth. The implementation details are in the code.




## Constant Velocity Hypothesis 
Forecast the future location of the vehicles with constant speed
Loc(t+1) = Loc(t) + speed(t)*Δt





## Learning-based Approach
Just use put bounding box into the neural netwok and output future waypoints.

