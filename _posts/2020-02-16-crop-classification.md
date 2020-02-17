---
layout: post
title: Crop Classification Using Satellite Imagery in the Orange River Valley, South Africa
---

![Image test]({{ site.url }}/images/three_pics.png)

## Overview
The Orange River is a major agricultural region in South Africa that has been stricken by drought in recent years. Accurate data is needed to improve agricultural growth and manage for vulnerability in the face of global change. Sub-Saharan Africa in particular struggles with incomplete or unreliable data in the agricultural sector. In 2018, the international community organized to launch the 50 X 2030 initiative, a commitment to collect better farm data with the goal of ending hunger.

<p>The goal of this project is to build a model that can identify a crop with satellite imagery which can help with monitoring more quickly and cheaply. I chose to focus on identifying vineyards because wine from Orange River is South Africa’s top exported agricultural product and is economically important to the region. 

<p> This project is a stepping stone to more advanced predictions such as crop yield prediction and predicted food security under future climate change scenarios.


## Data
The crop dataset was provided as a polygon shapefile with 2,497 agricultural fields. The crops growing on each field were verified in person and with drones in 2017.

There are 7 crop types present in the fields:

1. Cotton
2. Dates
3. Grass
4. Lucern
5. Maize
6. Pecan
7. Vacant
8. Vineyard
9. Vineyard & Pecan ("Intercrop")

This is a subset of the crop data provided.

![crop shapefile]({{ site.url }}/images/orange_river_crops.png)

## Methods

Footnotes are supported as part of the Markdown syntax. Here's one in action. Clicking this number[^fn-sample_footnote] will lead you to a footnote. The syntax looks like:

![test_train]({{ site.url }}/images/train_test_split.png)


## Results

Vivamus sagittis lacus vel augue rutrum faucibus dolor auctor. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Morbi leo risus, porta ac consectetur ac, vestibulum at eros.


### Lists

Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.


### Tables

Aenean lacinia bibendum nulla sed consectetur. Lorem ipsum dolor sit amet, consectetur adipiscing elit.

-----

Want to see something else added? <a href="https://github.com/poole/poole/issues/new">Open an issue.</a>

[^fn-sample_footnote]: Handy! Now click the return link to go back.
