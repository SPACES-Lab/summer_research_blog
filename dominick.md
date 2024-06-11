---
layout: default
title: Dominick's Page!
---
[Back Home](/README.md)
## Welcome to Dominick's Blog Page

On this page I will post 1-2 times a week on my progress throughout the project!

### Week 1(5/28 - 5/31) 

#### Overview 

During my first week of research it was important that I setup a great foundation to make data collection work as smoothy and accurately as possible. This included setting up the correct tools, familarizing myself with Connor's thesis, and reading documenation for API's. It was also important to identify the main goals of the project. Although, we are collecting air quality data from low cost sensors to compare with previous recorded data to analyze the effectiveness of these sensors. It is important to understand that as we are doing this collection we want to make the process as easy as possible to understand and follow for those who do not have a technical background.

#### Setting up My Environment 

On my first day I was tasked with settimg up my environment which involved the following: 

  1. Setting up Anaconda Envrionment
  2. Setting up Visual Studio Code
  3. Getting Juypter Notebooks to Work With Visual Studio Code

This was an essential first step as it created an environment where I have the necessary libraries needed to effectively collect data. Also, setting up the environment allowed for me to analyze Conner's Code and get a better understanding of the goals of the project and what comparisons, graphs and charts we will be creating when we collect our data. 

#### Understanding the Thesis 

After creating my environment I decided that it was in my best interest to throughly go through Conner's thesis and get a great understanding of the main concepts and his findings/results. It was especialy helpful looking through his methodolgy which cleared up a lot of gaps of knowledge that I had when going through his code. Throughout the weeks I will continue going through his thesis and code periodically so that I have as best of an undertsading of the science and math behind the graphs and charts so when we are done with our data collection showcasing that data will go as smoothly as possible. 

#### Learning How to Work With API's 

Before working with the API's we setup PurpleAIR sensors just to see how they functioned which can be seen on the real time map [here](https://map.purpleair.com/1/mAQI/a10/p604800/cC0#16.98/34.105185/-117.71215). Once we familarized ourselves with our sensors we wanted to create a group where we could add all the PurpleAir sensors on the roof and our sensors so that we could collect data in a group rather than individually. This involved reading PurpleAIR API documentation. 

##### Code Snippet(PurpleAir): 

![Creating Group](/images/image.png)

This is a quick snippet of creating a group for the PurpleAIR sensors. In the rest of the code we add the differnt members(sensors) into the group. 

Next, there was the process of working with the QuantAQ API. Unfortunately, there is no grouping function to access the sensor data so they must each be called individually. Using an api key and a basic get resposne fucntion we were able to acess the from the QuantAQ sensors including but not limited too PM1, PM2.5, and PM10 data which we also recieved from the PurpleAIR sensors. 

##### Code Snippet(QuantAQ): 

![Creating Group](/images/QuantAQ.png) 

Here in This image we see a basic API request from one of our QuantAQ sensors. This was then formatted with pandas and stored into a csv file wich could later be accessed for future comparisons and graphs! 


### Week 2(6/2 - 6/7) 
Week 2 was entailed with a lot of housekeeping and preparation for future task. We both were tasked with the creation of the github repository for storing our code. We first ran our coe to make sure it worked before pushing it into the repository. After running our code we went through the process of learing how to properly commit code to a github repository from vscode. I personally ran into a couple of problems but after several failed pushes to the repository I finally figured it out and learned a lot along the way. The PurpleAir group code and QuantAQ api call is now available on the repository 









