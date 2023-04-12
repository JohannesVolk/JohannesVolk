# 👋 Hi, my name is Johannes

I am studying Computer Science at the Technical University of Munich. My main areas of study are Machine Learning and Computer Vision.

I was nominated by TUM to do an international double degree in cooperation with the M.Sc. Data Science at the University of Queensland in Australia from 2024.

# What I use

<img src="https://upload.wikimedia.org/wikipedia/commons/f/f8/Python_logo_and_wordmark.svg" width ="100"/>
<img src="https://upload.wikimedia.org/wikipedia/commons/9/96/Pytorch_logo.png" width ="100"/>
<img src="https://upload.wikimedia.org/wikipedia/commons/e/e0/Ubuntu_logo_orange.png" width ="100"/>

## Check out some of the projects I've previously worked on

### [Point-Set Alignment Using Weak Labels](https://github.com/wngTn/synthetic_dcp)

You may want to see our [project report](https://github.com/wngTn/synthetic_dcp/blob/main/Project_Report.pdf) and [supplementary material](https://github.com/wngTn/synthetic_dcp/blob/main/Supplementary_Materials.pdf)

[![Visualization of the task](https://github.com/wngTn/synthetic_dcp/blob/main/assets/preview_video.png)](https://drive.google.com/file/d/10ExiSn-swk2jGCFB8Kq8de3IUifWTBWB/view?usp=share_link)

<img src="https://github.com/wngTn/synthetic_dcp/blob/main/assets/data_augmentation_vis.gif" width="pagewidth"/>



### [Search-Based Robustness Testing for traffic sign classifiers](https://gitfront.io/r/JohannesVolk/kGpYddba232z/traffic-sign-classifier-robustness-testing/)

Take a look at a excempt of our [presentation](https://drive.google.com/file/d/1pT7yqmQ0gV0R_XKGlxi67L1DDFZcRNim/view?usp=share_link).

In this project, we evaluated several algorithms for their performance in finding minimal "sticker attacks" against Deep Neural Networks for Traffic Sign Classification. For instance, we used Genetic Search, (Un-)/informed Search, Metaheuristic Search, Brute-Force Search. We compared [JMetalPy](https://github.com/jMetal/jMetalPy) and [Pymoo](https://pymoo.org/), two major optimization frameworks implemented in Python. We also explored more complex problems like multi sticker attacks and gradient-based search strategies.

The following visualizes the energy of the search space according to a simple fitness function considering uncertainty in the prediction of the traffic sign's label.
One can clearly notice the gradient leading to the area of greatest performance loss when attacked.

<img src="https://gitfront.io/r/JohannesVolk/kGpYddba232z/traffic-sign-classifier-robustness-testing/raw/rt_search_based/imgs/1_BasicAreaFitnessFunction.png" width="pagewidth"/>

Below is the search progression of a genetic algorithm that manages to converge to the optimal minimum discovered by exhaustive search.

[![](https://gitfront.io/r/JohannesVolk/kGpYddba232z/traffic-sign-classifier-robustness-testing/raw/rt_search_based/imgs/drive_video_preview.jpg)](https://drive.google.com/file/d/14JSosn3JALdvsQdWFVgUvGFUTY0LbB5e/view?usp=sharing)
