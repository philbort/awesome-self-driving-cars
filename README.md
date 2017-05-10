# Awesome Self-Driving Cars [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
> We wanted flying cars, instead we got 140 characters.              - *Peter Thiel* 

> We want self-driving cars, and we want them with an awesome list.  - Not *Peter Thiel*

## Introduction
A curated list of all awesome things related to self-driving car.

## Contributing
Contributions are highly appreciated. Please send me pull request. Make sure the stuff you add is actually awesome. We are **not** trying to include everything here, only awesome stuff.

## Table of Contents
- [Datasets](#datasets)
- [Simulators](#simulators)
- [Courses](#courses)
- [Papers & Blogs](#papers-blogs)
- [Big Players](#big-players)
- [Legislation](#legislation)

<a name="datasets" /> 

## Datasets
* [comma.ai's Driving Dataset [Videos]](https://github.com/commaai/research) - Seven and a quarter hours (~ 80 GB) of largely highway driving. With this dataset, comma.ai's founder [George Hotz](https://twitter.com/realgeorgehotz) trained a self-driving car [all by himself](https://www.bloomberg.com/features/2015-george-hotz-self-driving-car/).
* [Udacity's Driving Dataset [Videos]](https://github.com/udacity/self-driving-car/tree/master/datasets) - Eight hours (over 280 GB) of driving data collected for their [open source self-driving car challenges](https://www.udacity.com/self-driving-car). Udacity also provides convenient [scripts](https://github.com/rwightman/udacity-driving-reader) to port the data.
* [German Traffic Sign [Images]](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset) - More than 50,000 images and 40 classes of traffic signs. Excellent resource to benchmark your traffic sign classifier.
* [KITTI Vision Benchmark Suite [Images]](http://www.cvlibs.net/datasets/kitti/) - Large vision benchmark dataset with [objection detection](http://www.cvlibs.net/datasets/kitti/eval_object.php) evaluation training/testing images and leaderboard on cars and pedestrians.
* [Washington DC's Lidar Data](https://aws.amazon.com/blogs/publicsector/lidar-data-for-washington-dc-is-available-as-an-aws-public-dataset/) - Lidar point cloud of the entire Washington DC area is made available by the District of Columbia’s Office of the Chief Technology Officer (OCTO).

<a name="simulators" /> 

## Simulators
* [Udacity's Self-Driving Car Simulator](https://github.com/udacity/self-driving-car-sim) - This simulator is built for Udacity's Self-Driving Car Nanodegree to teach students how to train cars how to navigate road courses using deep learning. It is used for the project of [Behavioral Cloning](https://github.com/udacity/CarND-Behavioral-Cloning-P3).
* [Microsoft's AirSim](https://github.com/Microsoft/AirSim) - An open-source and cross platform simulator built for drones and other vehicles. AirSim is designed as a platform for AI research to experiment with deep learning, computer vision and reinforcement learning algorithms for autonomous vehicles. 
* [MIT's Moral Machine](http://moralmachine.mit.edu/) - Moral machine provides a *"platform for 1) building a crowd-sourced picture of human opinion on how machines should make decisions when faced with moral dilemmas, and 2) crowd-sourcing assembly and discussion of potential scenarios of moral consequence"*. If you are a fan of the [trolley problem](https://en.wikipedia.org/wiki/Trolley_problem), you can't miss this.
* [MIT's Google Self-Driving Car Simulator](https://scratch.mit.edu/projects/108721238/) - Self-driving car simulated completely by visual programming language [Scratch](https://en.wikipedia.org/wiki/Scratch_(programming_language)).

<a name="courses" />

## Courses
* [Udacity Self-Driving Car Nanodegree](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013) - Udacity's flagship program is sponsored by many self-driving car hiring partners. The nanodegree program includes 3 terms: 1) [Term 1: Computer Vision and Deep Learning](https://medium.com/self-driving-cars/term-1-in-depth-on-udacitys-self-driving-car-curriculum-ffcf46af0c08#.k5745vhdw), 2) [Term 2: Sensor Fusion, Localization, and Control](https://medium.com/udacity/term-2-in-depth-on-udacitys-self-driving-car-curriculum-775130aae502#.oh8xi152p), and 3) Term 3: Path Planning, Elective, and Systems. Each term costs $800.
* [MIT 6.S094: Deep Learning for Self-Driving Cars](http://selfdrivingcars.mit.edu/) - This class is an introduction to the practice of deep learning through the applied theme of building a self-driving car. It is open to beginners and is designed for those who are new to machine learning, but it can also benefit advanced researchers in the field looking for a practical overview of deep learning methods and their application. By the way, it's *free*!
* [BitTiger Build Your Own Autonomous Vehicle Mastery Program](https://www.bittiger.io/livecourses/2yG3CYMWRdAgDguzK) - Two weeks of live classes in Bay Area taught by engineers from Vector.ai on building a self-driving mini car from ground up. Topics include deep learning, ROS, sensors, computer vision, localization, mapping and control. The program costs $7,000.

<a name="papers-blogs" />

## Papers & Blogs
* [Computer Vision for Autonomous Vehicles: Problems, Datasets and State-of-the-Art](https://arxiv.org/pdf/1704.05519.pdf) - State-of-the-art survey on computer vision-related problems datasets and methods for self-driving cars.
* [End to End Learning for Self-Driving Cars](https://arxiv.org/abs/1604.07316) - Nvidia's ground breaking paper on using end to end learning (i.e., raw camera images as the input and steering commands as the output) with a Convolutional Neural Network (CNN) for behavioral cloning.
* [Learning a Driving Simulator](https://arxiv.org/abs/1608.01230) - [comma.ai](http://comma.ai/)'s approach for self-driving cars is based on an agent that learns to clone driver behaviors and plans maneuvers by simulating future events in the road. This paper investigates variational autoencoders with classical and learned cost functions using generative adversarial networks for embedding road frames. A transition model is learned in the embedded space using action conditioned Recurrent Neural Networks (RNNs). 
* [The Third Transportation Revolution](https://medium.com/@johnzimmer/the-third-transportation-revolution-27860f05fa91#.ga97y7w86) - Awesome blog post by [John Zimmer](https://twitter.com/johnzimmer) on [Lyft](https://www.lyft.com/)'s vision for self-driving cars. *Spoiler alert*, John predicts self-driving cars will account for the majority of Lyft rides within 5 years. And by 2025, private car ownership will all-but end in major U.S. cities.
* [16 Questions About Self-Driving Cars](http://a16z.com/2017/01/06/selfdriving-cars-frank-chen/) - [a16z](http://a16z.com/)'s [Frank Chen](https://twitter.com/withfries2) goes over the 16 most commonly asked questions, *technical* and *non-technical*, about self-driving cars.
* [Ways to think about cars](http://ben-evans.com/benedictevans/2015/7/27/ways-to-think-about-cars) - Awesome blog post by [a16z](http://a16z.com/)'s [Benedict Evans](https://twitter.com/BenedictEvans) on electric cars, on-demand car services, and self-driving cars.
* [Cars and second order consequences](http://ben-evans.com/benedictevans/2017/3/20/cars-and-second-order-consequences) - [Benedict Evans](https://twitter.com/BenedictEvans) on the impact of electric and autonomy on cars and beyond.

<a name="big-players" />

## Big Players
* [comma.ai](comma.ai/) - *The Android of self-driving cars (with the iPhone being Tesla)* claimed by their founder George Hotz. They open sourced their [dataset and software](https://github.com/commaai/research), [driving agent](https://github.com/commaai/openpilot), and [research platform](https://github.com/commaai/neo) after some disagreement with the [NHTSA](https://techcrunch.com/2016/10/28/comma-ai-cancels-the-comma-one-following-nhtsa-letter/).
* [Cruise Automation](https://www.getcruise.com/) - San Francisco-based startup was acquired by GM for $1B. They regularly post their self-driving videos on their [*YouTube*](https://www.youtube.com/channel/UCP1rvCYiruh4SDHyPqcxlJw) channel.
* [drive.ai](drve.ai/) - Silicon Valley startup founded by former lab mates out of Stanford University’s Artificial Intelligence Lab. Working on creating AI software for autonomous vehicles with deep learning. See their impressive drive demo [here](https://www.youtube.com/watch?v=GMvgtPN2IBU).
* [Ford](http://www.ford.com/) - Invested $1B in an artificial intelligence startup [Argo AI](https://www.argo.ai/), Ford plans to have [self-driving cars in commercial operation](https://shift.newco.co/fords-road-to-full-autonomy-36cb9cca330#.t03u8ir4c) for a ride-hailing service by 2021.
* [GM](https://www.gm.com/) - [Invested $500M in Lyft](https://www.nytimes.com/2016/01/05/technology/gm-invests-in-lyft.html) and [bought Cruise Automation for $1B](https://www.nytimes.com/2016/03/12/business/general-motors-to-buy-cruise-automation-in-push-for-self-driving-cars.html), GM is [expanding its R&D to Silicon Valley](https://www.nytimes.com/2017/04/13/business/gm-expands-self-driving-car-operations-to-silicon-valley.html) and targeting to soon test self-driving taxis on public roads.
* [nuTonomy](http://nutonomy.com/) - Startup spun out from MIT launched [world's first self-driving taxi service](https://techcrunch.com/2016/08/24/mit-spinout-nutonomy-just-beat-uber-to-launch-the-worlds-first-self-driving-taxi/) in Singapore. nuTonomy is currently expanding its self-driving car road test to Boston.
* [NIO](http://www.nio.io/) - electric car startup formerly known as NextEV, demonstrated [world's fastest (top speed of 160 mph) autonomous lap](http://www.nio.io/news/nio-sets-new-record-fastest-autonomous-car-world) with their EP9.
* [NVIDIA](http://www.nvidia.com/page/home.html) - NVIDIA is in a market dominant position for the use of their GPU for deep learning. Naturally self-driving car is a huge opportunity for them. NVIDIA already demonstrated their own self-driving car [BB8](https://blogs.nvidia.com/blog/2017/01/04/bb8-ces/). They also build their [open AI car computing platform](http://www.nvidia.com/object/drive-px.html) and [software development kit](https://developer.nvidia.com/driveworks).
* [Otto](http://ot.to/) - Self-driving truck startup acquired by Uber for $680M. Made to the awesome list by delivering beer from Denver to Colorado Springs with [120 miles of highway self-driving](https://www.youtube.com/watch?v=Qb0Kzb3haK8). Since the acquisition, Uber has [reportedly](https://backchannel.com/has-uber-killed-off-its-self-driving-trucks-3ebd2eb0e51) terminated the testing on self-driving turck and directed the talent of Otto to the development of their self-driving ride-sharing service.
* [Tesla](https://www.tesla.com/autopilot) - Currently the only automobile manufacturer sells hardware-ready vehicles. With thousands of self-driving capable vehicles already on the road and millions of miles driven, Tesla is using [fleet learning](https://electrek.co/2015/10/30/the-autopilot-is-learning-fast-model-s-owners-are-already-reporting-that-teslas-autopilot-is-self-improving/) to make their autopilot smarter and smarter.
* [Uber](http://uber.com) - Since self-driving cars are [existential crisis](http://www.recode.net/2017/2/20/14665438/self-driving-cars-uber-alphabet-google-waymo-brad-stone-upstarts-recode-podcast) to Uber, they have been actively building and testing their self-driving cars in [Pittsburgh, PA](https://newsroom.uber.com/pittsburgh-self-driving-uber/) and [Tempe, Arizona](https://www.bloomberg.com/news/articles/2017-02-21/uber-launches-self-driving-cars-in-arizona-after-california-ban). They also bought [Otto](http://ot.to/) and teamed up with [Volvo](http://www.theverge.com/2016/10/25/13404306/uber-volvo-self-driving-car-pittsburgh-spotted) and [Daimler](http://www.theverge.com/2017/1/31/14453704/uber-daimler-partnership-self-driving-cars-mercedes-benz-volvo) on deployment of self-driving cars. 
* [Udacity](https://www.udacity.com/) - Founded by self-driving car pioneer [Sebastian Thrun](https://twitter.com/SebastianThrun), Udacity is democratizing education and providing the best self-driving car education program through their [nanodegree](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013).
* [Waymo](https://waymo.com/) - Google's self-driving car company has driven way more miles than any other companies also with a much smaller [disengagement rate](https://www.dmv.ca.gov/portal/dmv/detail/vr/autonomous/disengagement_report_2016). 

<a name="legislation" />

## Legislation
* Arizona - [Executive order 2015-09](http://azgovernor.gov/file/2660/download?token=nLkPLRi1) was signed to direct all state agencies to *undertake any necessary steps to support the testing and operation of self-driving vehicles on public roads within Arizona*. The executive order also specifies that in Arizona the operator of a self-driving vehicle does *not* have to be physically inside the vehicle. The vehicle can be directed remotely in self-driving mode.
* [California](https://www.dmv.ca.gov/portal/dmv/detail/vr/autonomous/bkgd) - Application required for [testing self-driving cars](https://www.dmv.ca.gov/portal/dmv/detail/vr/autonomous/testing). Manufacturers are required to provide [accident reports](https://www.dmv.ca.gov/portal/dmv/detail/vr/autonomous/autonomousveh_ol316+) and [disengagement reports](https://www.dmv.ca.gov/portal/dmv/detail/vr/autonomous/disengagement_report_2016). The regulations for [post-testing deployment](https://www.dmv.ca.gov/portal/dmv/detail/vr/autonomous/auto) of self-driving cars have been drafted and will establish the requirements for manufacturers to meet prior to operation on California’s on public roads.
* Texas - Bill [SB 2205](http://www.capitol.state.tx.us/Search/DocViewer.aspx?ID=85RSB022051A&QueryText=%22SB+2205%22&DocType=A) is proposed to implement minimum safety requirements and accelerate testing of self-driving cars on public roads. The bill passed the Texas Senate Transportation Committee and it is currently pending Senate debate and referral to the House.
* Virginia - Arguably the most friendly state to self-driving cars with no application or permit required and [$25M per year fund](https://www.washingtonpost.com/local/trafficandcommuting/virginia-wants-to-steal-some-of-californias-driverless-thunder/2017/04/23/a4bc6b54-206c-11e7-a0a7-8b2a45e3dc84_story.html?utm_term=.cfaac3ec962d) set to facilitate self-driving cars. [Virginia Automated Corridors](https://governor.virginia.gov/newsroom/newsarticle?articleId=8526) is announced to offer self-driving car developers the opportunity to *test their technologies on Virginia roads covering more than 70 miles of interstates and arterials in the Northern Virginia region*.
