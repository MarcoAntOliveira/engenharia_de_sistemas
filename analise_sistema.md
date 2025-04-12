## Sistema drone

### Nodes
Each node in ROS should be responsible for a single, modular purpose, e.g. controlling the wheel motors or publishing the sensor data from a laser range-finder. Each node can send and receive data from other nodes via topics, services, actions, or parameters.<br>
![alt text](https://docs.ros.org/en/foxy/_images/Nodes-TopicandService.gif)
### Topics
ROS 2 breaks complex systems down into many modular nodes. Topics are a vital element of the ROS graph that act as a bus for nodes to exchange messages.<br>
![alt text](https://docs.ros.org/en/foxy/_images/Topic-SinglePublisherandSingleSubscriber.gif)<br>
A node may publish data to any number of topics and simultaneously have subscriptions to any number of topics.<br>
![alt text](https://docs.ros.org/en/foxy/_images/Topic-MultiplePublisherandMultipleSubscriber.gif)
### Services
 Services are another method of communication for nodes in the ROS graph. Services are based on a call-and-response model versus the publisher-subscriber model of topics. While topics allow nodes to subscribe to data streams and get continual updates, services only provide data when they are specifically called by a client.<br>
 ![alt text](https://docs.ros.org/en/foxy/_images/Service-SingleServiceClient.gif)
 ![alt text](https://docs.ros.org/en/foxy/_images/Service-MultipleServiceClient.gif)
