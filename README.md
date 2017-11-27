# data-day-tx-2018

This is the talk given by Graham Ganssle and Steve Purves at [Data Day Texas](http://datadaytexas.com/) 2018. This talk was given in conjunction with Lynn Pausic and Chris LaCava's talk about how human bias is preserved in machine learning systems.

## The Aim
We show how biased training data biases results of model outputs by assessing the qualification of loan applicants based on US Census data. We train our model on a dense, varied dataset and quantify the difference in apparent loan-worthiness with respect to applicant gender.

## Methods
We use a graph convolutional network to predict a node property (credit worthiness) from other node properties and edge connections to other credit applicants.


## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">data-day-TX-2018</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Lynn Pausic, Graham Ganssle, Steve Purves, Expero Inc</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>, **except where otherwise noted**.

This work borrows heavily from *Graph Convolutional Networks* by Thomas Kipf and Max Welling, licensed MIT: ©Thomas Kipf, 2016. You can find their excellent paper [here](https://arxiv.org/abs/1609.02907).
