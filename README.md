# Trip-destination-Prediction
The purpose of trip destination prediction is to identify the latitude and longitude points of the user based on features like day, hour, departure zone, partial_historical data of user. 
One of the usecases of trip destination prediction is **Ride-Sharing Services**: Platforms like Uber and Lyft use destination prediction to:
Match riders with drivers efficiently.
Optimize driver routing and reduce wait times.
In this project, Geolife Trajectories 1.3 data is trained in LSTM model for destination prediction.
Trip destination prediction plays an important role in exploring urban travel patterns.
Accurate prediction can improve the efficiency of traffic management and the quality of
location-based services. Here, a deep learning structure that contains three components:
travel information extraction, classification learning mechanism, and output module is proposed.
Three types of information (the partial trajectory of on-going trips, historical trajectories,
and related external information) are extracted in the first component. Then,
the classification learning mechanism chooses different methods (i.e. Long Short-Term
Memory network and Embedding technology) according to the characteristic of variables.
Finally, an output layer that integrates the prior information about destinations is constructed.
Two open-source trajectory datasets are used to validate the effectiveness of the
proposed model. Results show that the proposed model outperforms benchmark models
using only part of the information or using all of the information but ignore the classification
learning mechanism. The performance of the proposed model under different call
types and travel durations is further explored. The result of this study will help understand
travel behaviour in urban cities.
