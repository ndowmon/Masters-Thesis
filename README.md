# Masters Thesis

My masters thesis shares the work I completed as a graduate research assistant at MIT. This work describes two code bases (V1 - Python, V2 - Java) developed for the research sponsor, a fortune 100 company. The code is private at the request of the research sponsor.

## Abstract

The goal of this research is to develop a framework for detecting anomalies in network traffic data on highly complex computer networks. In this research, I present the Enseble Outlier Detection System, a new framework for detecting anomalies in multidimensional network traffic data. The system meets six design requirements which ensure that the system can meet the needs of the sponsor organization's cyberscurity teams both now and in the future. In particular, this system improves on many existing anomaly detection systems by maintaining scalability for extremely large computer networks and resiliency to non-stationary data, re-establishing its own baselines as the network changes over time. I also present the Explorer tool, designed for cyberscurity analysts to interpret the cause of high anomaly scores on certian data points and to annotate each data point atomically. I ensure scalability by treating all fields in a data point as indepenedent of one another. Preliminary results suggest that this treatment will not affect system performance, as many anomalous data points exhibit multiple anomalous fields at a time, increasing the outlier predictions for the interpretations of various anomalies in network traffic from the sponsoring institution's dataset, and achieves performance values which can detect real-time anomalies in enterprise computer networks.

Thesis Supervisor: Dr. Abel Sanchez
