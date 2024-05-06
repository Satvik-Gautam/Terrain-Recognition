# Terrain-Recognition
TerrainNet uses several deep learning techniques to better understand the terrain.

It uses CNN  techniques to classify the terrain(classes like - sandy , concrete , marshy , gravel etc). The CNNs are great because of their reduced network complexity and the fact that they are able to learn important features from the images , this helps them easily generalize .

texture extraction is used to give several essential insights about the terrain such as the associated roughness , bumpiness and slipperiness , these insights can be further used to guide autonomous vehichles along the most effecient and safest paths. This can also help the Ministry in vehichle deployment .

It further uses Autoencoders for obstacle and anomaly detection.The autoencoders are trained on differnt sorts of natural terrains . The autoencoders when used on a terrain with some anomalies will be able to tell wether or not there is something out-of-place , also they will tell us the exact location of it.This can greatly aid the Defence Ministry as the anomalies can be anything from mines to sniper hideouts to man-made underground cave entries.


RNNs are employed to effeciently handle real-time video inputs, RNNs use the computations done on the previous inputs to form an understanding and hence will be used to decrease the computations required in each subsequent frame.They will primarily be used to segment the different terrains present in any particular frame , due to the similarities between video frames this segmentation provides great context for the next frame's terrain distribution .




TerrainNet can be employed for various defence related purposes such as optimal path planning, vehichle deployment, search and rescue operations, mine detection etc
