# Future Boundingbox Prediction 
We perform basic occupancy forecasting from ground-truth bounding box with the below two approaches. Then compare them with some metrics such as IOU and L2 distance between prediction and ground-truth. The implementation details are in the code.




## Constant Velocity Hypothesis 
Forecast the future location of the vehicles with constant speed
Loc(t+1) = Loc(t) + speed(t)*Δt





## Learning-based Approach
Just use put bounding box into the neural netwok and output future waypoints.


## Analysis

We could see that the IOU is decreasing as the dt 

![image](https://github.com/Heng-Henry/BoundingBox-Prediction/assets/90209480/f9d2ecc0-6c60-4fd8-9d9d-32b08b9bdf30)

### learn dt = 0.5
![image](https://github.com/Heng-Henry/BoundingBox-Prediction/assets/90209480/83949e7b-66d1-482c-b78f-18f41fe9a491)


### learn dt = 1.0
![image](https://github.com/Heng-Henry/BoundingBox-Prediction/assets/90209480/fbb8127d-4421-40db-b079-1b69d968b790)


### learn dt = 2.0
![image](https://github.com/Heng-Henry/BoundingBox-Prediction/assets/90209480/2da40d96-b9c2-462c-9c7a-dad562330f7e)




