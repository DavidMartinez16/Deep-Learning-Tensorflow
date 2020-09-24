# Human Activity Recognition

Human Activity Recognition (HAR) has been a challenging problem yet it needs to be solved. It will mainly be used for eldercare and healthcare as an assistive technology when ensemble with other technologies like Internet of Things(IoT). HAR can be done with the help of sensors, smartphones or images.

The [Dataset](https://www.cis.fordham.edu/wisdm/dataset.php) contains data collected through controlled, laboratory conditions.

## Raw Time Series Data
* Number of examples: 1,098,207
* Number of attributes: 6
* Missing attribute values: None
* Class Distribution
    * Walking: 424,400 (38.6%)
    * Jogging: 342,177 (31.2%)
    * Upstairs: 122,869 (11.2%)
    * Downstairs: 100,427 (9.1%)
    * Sitting: 59,939 (5.5%)
    * Standing: 48,395 (4.4%)
 
For this case, i built a Convolutional Neural Network to classify each class, and I got accuracy values for the training and the validation samples closer to 90 %, in the following picture you'll see the training curve.

![tc](https://user-images.githubusercontent.com/63115543/94209803-cc085580-fe92-11ea-96d3-154c34cfa567.jpg)

And for the testing samples i got the following confusion matrix with 88 % of accuracy.

![cm](https://user-images.githubusercontent.com/63115543/94209800-c9a5fb80-fe92-11ea-9645-d9b12af87208.jpg)
