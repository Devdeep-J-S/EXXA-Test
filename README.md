
# GSoC EXXA Test
## 2023
# ML4Sci

---

The purpose of EXXA is to use machine learning to analyze exoplanets, their systems, and their formation. 

While there is plenty of public astronomical data available, e.g, Kepler and NASA, it is often too uncertain or too sparse for the training of robust, generalizable models. As a result, simulated data is frequently used to supplement or replace observations. This allows the creation of arbitrarily large datasets where all variables are known exactly. 

The importance of simulated data cannot be overstated for machine learning in astronomy. Therefore, an understanding of its creation and use is essential for successful projects. This test will focus on that idea.


## Overview
---
One of the most successful methods to detect exoplanets is using light curves. Several thousand planets have been discovered this way. The basic idea is that exoplanets crossing in front of their host stars will obscure part of the star, which decreases the amount of light that we see from that star. By carefully measuring the brightness over time, planets can be identified by the periodic dimming. The extent of the dimming depends on the specific parameters of the stellar system.

## Task
---
Using these concepts, create a simulated dataset of transit curves. Include as many physical and system parameters as you think are necessary. Feel free to supplement the synthetic data with observational data. Use this data to train a classifier that determines whether or not a given transit curve shows the presence of a planet.

## Colab link 
---
https://colab.research.google.com/drive/1pBhsuvO3JfGBD29M72WTqyt9fXA8xql1?usp=sharing


