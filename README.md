# Awesome Self-Driving Cars [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
> We wanted flying cars, instead we got 140 characters.              - Peter Thiel 

> We want self-driving cars, and we want them with an awesome list.  - Not Peter Thiel

## Introduction
A curated list of all awesome things related to self-driving car.

## Contributing
Contributions are highly appreciated. Please send me pull request. Make sure the stuff you add is actually awesome. We are **not** trying to include everything here, only awesome stuff.

## Table of Contents
- [Datasets](#datasets)
- [Simulators](#simulators)
- [Courses](#courses)
- [Papers](#papers)
- [Big Players](#big-players)

<a name="datasets" />
## Datasets
* [comma.ai's Driving Dataset [Videos]](https://github.com/commaai/research) - 7 and a quarter hours (~ 80 GB) of largely highway driving. With this dataset, comma.ai's founder [George Hotz](https://twitter.com/realgeorgehotz) trained a self-driving car [all by himself](https://www.bloomberg.com/features/2015-george-hotz-self-driving-car/).
* [Udacity's Driving Dataset [Videos]](https://github.com/udacity/self-driving-car/tree/master/datasets) - 8 hours (over 280 GB) of driving data collected for their [open source self-driving car challenges](https://www.udacity.com/self-driving-car). Udacity also provides convinient [scripts](https://github.com/rwightman/udacity-driving-reader) to port the data.
* [German Traffic Sign [Images]](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset) - More than 50,000 images and 40 classes of traffic signs. Excellent resource to benchmark your traffic sign classifier.

<a name="simulators" />
## Simulators
* [Udacity's Self-Driving Car Simulator](https://github.com/udacity/self-driving-car-sim) - This simulator is built for Udacity's Self-Driving Car Nanodegree to teach students how to train cars how to navigate road courses using deep learning. It is used for the project of [Behavioral Cloning](https://github.com/udacity/CarND-Behavioral-Cloning-P3).
* [Microsoft's AirSim](https://github.com/Microsoft/AirSim) - An open-source and cross platform simulator built for drones and other vehicles. AirSim is designed as a platform for AI research to experiment with deep learning, computer vision and reinforcement learning algorithms for autonomous vehicles. 

<a name="courses" />
## Courses
* [Udacity Self-Driving Car Nanodegree](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013) - Udacity's flagship program is sponsored by many self-driving car hiring partners. The nanodegree program includes 3 terms: 1) [Term 1: Computer Vision and Deep Learning](https://medium.com/self-driving-cars/term-1-in-depth-on-udacitys-self-driving-car-curriculum-ffcf46af0c08#.k5745vhdw), 2) [Term 2: Sensor Fusion, Localization, and Control](https://medium.com/udacity/term-2-in-depth-on-udacitys-self-driving-car-curriculum-775130aae502#.oh8xi152p), and 3) Term 3: Path Planning, Elective, and Systems. Each term costs $800.
* [MIT 6.S094: Deep Learning for Self-Driving Cars](http://selfdrivingcars.mit.edu/) - This class is an introduction to the practice of deep learning through the applied theme of building a self-driving car. It is open to beginners and is designed for those who are new to machine learning, but it can also benefit advanced researchers in the field looking for a practical overview of deep learning methods and their application. By the way, it's *free*!

<a name="papers" />
## Papers
* [End to End Learning for Self-Driving Cars](https://arxiv.org/abs/1604.07316) - Nvidia's ground breaking paper on using end to end learning (i.e., raw camera iamges as the input and steering commands as the output) with a Convolutional Neural Network (CNN) for behavioral cloning.
* [Learning a Driving Simulator](https://arxiv.org/abs/1608.01230) - [comma.ai](http://comma.ai/)'s approach for self-driving cars is based on an agent that learns to clone driver behaviors and plans maneuvers by simulating future events in the road. This paper investigates variational autoencoders with classical and learned cost functions using generative adversarial networks for embedding road frames. A transition model is learned in the embedded space using action conditioned Recurrent Neural Networks (RNNs). 

<a name="big-players" />
## Big Players
* [comma.ai](comma.ai/) - *The Android of self-driving cars* claimed by their founder George Hotz. They open sourced their [dataset and software](https://github.com/commaai/research), [driving agent](https://github.com/commaai/openpilot), and [research platform](https://github.com/commaai/neo) after some disagreement with the [NHTSA](https://techcrunch.com/2016/10/28/comma-ai-cancels-the-comma-one-following-nhtsa-letter/).
* [Otto](http://ot.to/) - Self-driving truck startup acquired by Uber for $680M. Made to the awesome list by delivering beer from Denver to Colorado Springs with [120 miles of highway self-driving](https://www.youtube.com/watch?v=Qb0Kzb3haK8).
* [Tesla](https://www.tesla.com/autopilot) - *The iPhone of self-driving cars* with George Hotz's analogy. With thousands of self-driving capable vehicles on the road and millions of miles driven, Tesla is using [fleet learning](https://electrek.co/2015/10/30/the-autopilot-is-learning-fast-model-s-owners-are-already-reporting-that-teslas-autopilot-is-self-improving/) to make their autopilot smarter and smarter.
* [Uber](http://uber.com) - Since self-driving cars are [existential crisis](http://www.recode.net/2017/2/20/14665438/self-driving-cars-uber-alphabet-google-waymo-brad-stone-upstarts-recode-podcast) to Uber, they have been actively building and testing their self-driving cars in [Pittsburgh, PA](https://newsroom.uber.com/pittsburgh-self-driving-uber/) and [Tempe, Arizona](https://www.bloomberg.com/news/articles/2017-02-21/uber-launches-self-driving-cars-in-arizona-after-california-ban). They also bought [Otto](http://ot.to/) and teamed up with [Volvo](http://www.theverge.com/2016/10/25/13404306/uber-volvo-self-driving-car-pittsburgh-spotted) and [Daimler](http://www.theverge.com/2017/1/31/14453704/uber-daimler-partnership-self-driving-cars-mercedes-benz-volvo) on deployment of self-driving cars. 
* [Udacity](https://www.udacity.com/) - Founded by self-driving car pioneer [Sebastian Thrun](https://twitter.com/SebastianThrun), Udacity is democratizing education and providing the best self-driving car education program through their [nanodegree](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013).
* [Waymo](https://waymo.com/) - Google's self-driving car company has driven way more miles than any other companies also with a much smaller [disengagement rate](https://www.dmv.ca.gov/portal/dmv/detail/vr/autonomous/disengagement_report_2016). 
