# Amazon-Product-Reviews - Sentiment-Analysis


## **Table of Contents**

[1. Problem Statement](#problem-statement)   
[2. My Approach](#my-approach)   
[3. Technologies used](#technologies-used)   
[4. Project Objectives](#project-objectives)   
[5. Steps to run my deployed project on your local server](#steps-to-run-my-deployed-project-on-your-local-server)   
[6. Data source files](#data-source-files)   

---

### **Problem Statement**

It is observed that the maximum number of customers look at product reviews before they make a purchase. Survey results show that positive product reviews are a key factor for purchasing by 57% of Amazon buyers (Statista, 2019). 

As product reviews are often the deciding factor for many customers, it’s very important to have a well-automated system for monitoring them.

The traditional manual process of Amazon product reviews is time-consuming and inefficient when millions of reviews are being posted all the time. It doesn’t show any trend or patterns over time. Moreover, it is tough to understand customers’ sentiment towards any product or its delivery.

---

### **My Approach**

I will be classifying Amazon customer reviews from the source files mentioned below, into 3 categories of positive, negative and neutral. We used Text Classification and Time Series Analysis to solve this problem statement.  

An automated system was developed to analyze and monitor an enormous number of reviews. By monitoring the entire review history of products, we analyzed the tone, language, keywords, and trends over time to provide valuable insights that increase the success rate of existing and new products as well as marketing campaigns. 

*Sentiment Analysis* is an emerging tool that helps businesses differentiate and categorize opinions about their products, services and brand image. This technique is used in Natural Language Processing by converting unstructured text into data that can be analysed.

*Time Series* Analysis helps in highlighting trends to forecast sentiment trends for particular subcategories in the future. Brands can discover many hidden trends in customer sentiments from historical data.


![WhatsApp Image 2022-12-11 at 17 39 18](https://user-images.githubusercontent.com/118181589/206913431-8275a984-8b76-47a2-b47e-cc37c2b4e66c.jpg)


---

### **Technologies Used**
![image](https://user-images.githubusercontent.com/118181589/206911991-3b04872d-0784-42d6-b043-1d14912d5cbe.png)



---

### **Project Objectives**
Reviews Preprocessing and Cleaning

Story Generation and Visualization from reviews - Tableau

Extracting Features from Cleaned reviews

Model Building: Sentiment Analysis

Model Building: Time Series Analysis

Model Deployment

---

### **Steps to run my deployed project on your local server**
Steps to set up your environment, and run my project on your local server 

Go to your command prompt/terminal, change your directory to the folder that includes all the files in the deploymed_files folder 
and enter the following codes:

1. pip install virtualenv
2. virtualenv ENV
3. ./ENV/Scripts/activate
4. install all required dependencies listed in requirements.txt
5. To run our website on your local server, enter the code python app.py
6. Enter the ip address generated, on your browser's search bar. 

---

### **Data Source Files**

http://jmcauley.ucsd.edu/data/amazon/

Per-category files (4 datasets used):
1. Home and Kitchen - reviews 
2. Home and Kitchen - metadata
3. Musical Instruments - reviews
4. Musical Instruments - metadata
