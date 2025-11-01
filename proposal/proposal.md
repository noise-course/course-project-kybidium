# NetML - Segment Addendum

## Project Participants


| Name     | Kai Lee      | Luis Ojeda   |
| -------- | ------------ | ------------ |
| CNET     | ka1          | luisojeda    |
| Role     | Contributor  | Contributor  |

## Project Description

The NetML library is useful in processing packet captures but there are other features that could improve model accuracy when calculated and used through the library. For our final project we plan on contributing to the NetML GitHub Repository by adding additional features such as **Segment Count per Flow** (number of distinct segments transmitted), **Segment Rate (segments per second)** (captures delivery pacing and adaptive streaming responsiveness), **Average Segment Size and Variance** (identifies bitrate switching patterns), and **Segment Throughput** (mean bytes per segment interval, complementing existing packet throughput features). In addition to these features we hope to gain a better understanding of the library and perhaps make further enhancements. We are aiming to learn more about state-of-the-art ML and networks libraries, contribute to an open-source project, and solidify our understanding of the influence of different features on ML model performance and its network applications.

## Data

To evaluate whether our contributions to the library improve model performance, we will rely on data that we will capture from a video stream using Wireshark.

## Deliverables

In a Jupyter Notebook, we expect to try linear regression and a random forest classifier when we evaluate the features we will create. We will also evaluate using all of the models in the netML library. We will benchmark the performance of the models without using the added features and compare against the performance when the features are used. To evaluate each performance we will likely use accuracy, ROC curves, and other evaluation methods. 
