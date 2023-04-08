# Problem statement
A Machine learning approch to detect diseases in tomato leaves.This is to develop an accurate and efficient system that can automatically identify the presence of diseases in tomato leaves from images. The system should be able to classify images into different categories based on the type of disease present and provide recommendations for appropriate treatment measures.

# Dataset used
The dataset used for images is the PlantVillage dataset from UPenn

# MLsolutionforagriculture
This machine learning model is designed to help farmers make informed decisions about crop selection, disease prevention, fertilizer application, and market trends. It is based on a deep learning architecture that leverages convolutional neural networks (CNNs) to analyze images of leaves and other supervised algorithms to analyze other features.

# Inspiration
Karnataka: Tomato prices crash, ryots allow crops to wither in Kolar
TOI ,Ranganath Krishnaswamy / TNN / Jul 22, 2022, 09:16 IS ..
Tomato, onion growers in tears following price crash in Karnataka
Hindustan Times , PTI | | Posted by Pathi Venkata Thadhagath
Tomato prices surge as rains damage crop
By Sutanuka Ghosal, ET BureauLast Updated: Aug 12, 2022, 12:53 AM IST

Tomato is an integral part of every household throughout India as it is the basic ingredient of almost every dish in the Indian cuisine.
In recent years, the tomato industry in India has faced a significant challenge in the form of tomato leaf diseases, which have caused immense losses for farmers. According to a report by The Economic Times, farmers in Karnataka alone have reported losses of over Rs 500 crore due to diseases in tomato plants.
This inspired me to create a model that provides a solution that can help farmers detect diseases in tomato plants accurately and quickly remedy it.

# What it does ?
This project aims to revolutionize the way we detect diseases in tomato plants.This project leverages the power of Convolutional Neural Networks (CNNs) to accurately detect diseases in tomato leaves from images.This user-friendly GUI allows users to simply upload an image of a tomato leaf and receive an decently accurate prediction of any disease present. Additionally, our GUI provides remedies for the detected diseases in Kannada, making it accessible to a wider audience in Karnataka.
The importance of staying up-to-date on the market trends of tomato production in today's world is crucial.Therefore, our project also includes a visualization of tomato markets in major cities in Karnataka. This feature provides valuable insights into the tomato industry and helps farmers make informed decisions about their crops.I hope this project will contribute to the agricultural industry and empower farmers in Karnataka to make informed decisions about their crops.I welcome any feedback and contributions to make our project even better!

# Existing solution and modifications:

There are some existing solutions that analyses the image and apply CNN to predict the disease present but this is a modified model that specifically targets the Karnataka farmers and tomato harvesters therefore it provides remedies and solutions specifically catered to them.
It is also an Intel oneAPI optimised project hence it provides faster,optimised algorithms and computations.

# Comparision between InteloneAPI and others

Intel OneAPI provides a comprehensive set of tools, libraries, and frameworks that can help optimize code for specific hardware architectures, which can lead to significant improvements in execution times. This level of performance optimization can be particularly valuable for users working on computationally intensive tasks that require high levels of processing power.In context to this project,CNN's prediction happens in seconds unlike in other platforms.Almost all epochs are processed for the whole of training dataset within seconds whereas in other platforms it takes significantly longer time.This was also done without any RAM crashes during the processing.And to whoever uses it,it is clear that Intel OneAPI offers a powerful and versatile set of tools that can help developers and researchers achieve their goals with maximum efficiency and performance.

# How I built it ?

<li>=> IMPORT LIBRARIES
=> EDA AND LABEL IMAGES
=> SPLIT THE DATA AND PREPROCESS IT
=> BUILD A MODEL
=> TRAIN THE MODEL
=> ANALYSE THE OUTPUT</li>

# What I learned ?
Since I am a beginner in ML, I learnt a lot terms,explored a lot of domains and gained a vast array of knowledge,some of it include
=>INTEL ONEAPI AND ITS TOOLKITS : Intel OneAPI is a software development kit that enables developers to create high-performance applications that can run on a variety of hardware platforms, including CPUs, GPUs, and FPGAs. OneAPI offers a set of tools, libraries, and frameworks that developers can use to optimize their code for specific hardware architectures, which can lead to faster and more efficient execution times.
=> AWARENESS OF ECONOMY : Searching for a problem statement made me aware of the situation,the need for the model and modification required however it also provided me knowledge how these prices vastly affect the economy as a whole.
=> EDA : From finding the required dataset to exploring it,I gained a lot of knowledge on Data acquisition and preprocessing.
=> PLANT PATHOLOGY : I likely gained knowledge on different plant diseases and how to remedy it.
=> MACHINE LEARNING : I likely gained knowledge on CNN and its overall working.
=> AGRICULTURAL TRENDS: I likely gained insight into current trends in agriculture and the challenges facing farmers, such as the need for sustainable and efficient crop production.
