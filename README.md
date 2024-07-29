# 👋 Hi, my name is Johannes

I am a postgraduate studying Computer Science at the Technical University of Munich and Data Science at the University of Queensland.

## Check out some of the stuff I've previously worked on


### [A Framework for Analysing Delays within Public Transport Networks](https://github.com/JohannesVolk/data7001-project)

We propose a framework to analyze the live compared to the historical network delay in public transport systems.

You may want to see our [project report](https://github.com/JohannesVolk/data7001-project/blob/main/report.pdf).

### [Point-Set Alignment Using Weak Labels](https://github.com/wngTn/synthetic_dcp)

You may want to see our [project report](https://github.com/wngTn/synthetic_dcp/blob/main/Project_Report.pdf) and [supplementary material](https://github.com/wngTn/synthetic_dcp/blob/main/Supplementary_Materials.pdf)

In this course project we used the DL-based Point Set Registration Method Deep Closest Point (DCP) to detect heads/faces in 3D Operation Room scenes. We assembled a new dataset to synthetically train our model, which ultimately performed slightly better on the synthetic data than non-DL-based methods such as FilterReg.

[![Visualization of the task](https://github.com/wngTn/synthetic_dcp/blob/main/assets/preview_video.png)](https://drive.google.com/file/d/10ExiSn-swk2jGCFB8Kq8de3IUifWTBWB/view?usp=share_link)

<img src="https://github.com/wngTn/synthetic_dcp/blob/main/assets/data_augmentation_vis.gif" width="pagewidth"/>


### [Search-Based Robustness Testing for traffic sign classifiers](https://gitfront.io/r/JohannesVolk/kGpYddba232z/traffic-sign-classifier-robustness-testing/)

Take a look at a excempt of our [presentation](https://drive.google.com/file/d/1pT7yqmQ0gV0R_XKGlxi67L1DDFZcRNim/view?usp=share_link).

In this project, we evaluated several algorithms for their performance in finding minimal "sticker attacks" against Deep Neural Networks for Traffic Sign Classification. For instance, we used Genetic Search, (Un-)/informed Search, Metaheuristic Search, Brute-Force Search. We compared [JMetalPy](https://github.com/jMetal/jMetalPy) and [Pymoo](https://pymoo.org/), two major optimization frameworks implemented in Python. We also explored more complex problems like multi sticker attacks and gradient-based search strategies.

The following visualizes the energy of the search space according to a simple fitness function considering uncertainty in the prediction of the traffic sign's label.
One can clearly notice the gradient leading to the area of greatest performance loss when attacked.

<img src="https://gitfront.io/r/JohannesVolk/kGpYddba232z/traffic-sign-classifier-robustness-testing/raw/rt_search_based/imgs/1_BasicAreaFitnessFunction.png" width="pagewidth"/>

Below is the search progression of a genetic algorithm that manages to converge to the optimal minimum discovered by exhaustive search.

[![](drive_video_preview.PNG)](https://drive.google.com/file/d/1DYT_7pp1Wa_OjKDNBrGEyHKjGc3wRqud/view)
