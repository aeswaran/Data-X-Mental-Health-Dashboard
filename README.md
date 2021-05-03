
### IEOR 135 / 290: Applied Data Science with Venture Applications


# Data-X-Mental-Health-Dashboard
 
This repository contains all code notebooks used to create a mental health dashboard analyzing 16 different U.S. universities.

## 📁 About The Project

Due to the COVID-19 pandemic, our world has shifted everyone’s day to day activities to online platforms. With the increased number of hours sitting in front of technology and limited face-to-face interactions, numerous mental health concerns have emerged. Driven to action, a group of four UC Berkeley students, set out to create an interactive tool that provides an analytical visual of mental health trends for various public and private universities across the nation. The project aims to provide a snapshot of mental health status among college students and track changes in prevalence of mental health issues by using anonymized Reddit data.


## 🔍 The Problem The Team Aimed to Solve, and The Solution

**The Problem**

For the last thirteen months, many of us have been in social isolation, unable to visit family, friends, and loved ones in-person; unable to go to class; to the office; to travel; to attend concerts and sports events. The places where we once sought interaction, such as school and work, have slowed their operations, forcing us to shift to a work-from-home situation. These measures have certainly curbed the impact of a deadly virus, but in return have taken a toll on our mental health.

While individuals of all demographics have been struggling, we must face the reality: college students have been arguably facing the most adversity during the pandemic. In fact, according to the National Institute of Health, (71% of college students) indicated increased stress and anxiety due to the COVID-19 outbreak. Multiple stressors were identified that contributed to the increased levels of stress, anxiety, and depressive thoughts among students, including fear and worry about their own health and of their loved ones, difficulty in concentrating, disruptions to sleeping patterns, decreased social interactions due to physical distancing, and increased concerns on academic performance. This in turn has made it difficult for professors to gauge workload of their classes and for mental health clinics to better serve their patients.

Thus the team hoped to alleviate the concerns of professors, psychologists, physicians and other organizations by solving this problem and ultimately increase dialogue and improve outcomes for individuals and families with mental health needs.

**The Solution**

The team's solution involves producing a high quality analysis that will serve as a point of departure for organizations trying to conduct studies on mental health, an often complex matter to assess. The final product is an interactive dashboard that displays key mental health trends for both private and public universities, as well as a sentiment analysis using social media data. Users can choose one of the 16 universities using a dropdown, as well as one of the mental health keywords available. With the dashboard, the team hopes to provide an in-depth look at mental health and the social effects that may not be able to be analyzed due to public health conditions and to further educate the masses about mental health. The team's final product can be found here: http://covid19-social-media-trends.herokuapp.com/

The team hopes that their studies of mental health through social media encourages current psychologists, scientists and other researchers to be able to conduct longitudinal studies of mental health past COVID-19, potentially involving studies of different demographics such as children and the elderly. They aim to utilize their results as evidence for potential policy implementation and revision at large universities like UC Berkeley, where the lives of numerous students are at stake and at the discretion of higher authorities who make decisions that can impact student wellbeing.

## 💡 What's Inside the Folders

**Web Scraping Code for Data Collection:** 
To efficiently collect data, the team used a python notebook with web scraping code. The notebook can be found in this folder. To get specific posts from each university, the team changed the subreddit thread according to each university, and the before and after UNIX codes using time conversions.

**Pre-Pandemic Data: EDA, Polarities:** 
Using the code from the Web Scraping Code folder, the team collected pre-pandemic data for 16 universities. The data is stored in this folder. With the pre-pandemic data, the team calculated specific mental health keyword frequencies per university, as well as the polarity distributions for each university over a span of 11 months. The word frequency calculations and notebook can be found in a subfolder called Word Frequency Per University. Similarly, the polarity distribution calculations and notebook can be found in a subfolder called Polarities for Each University. The results of both of the notebooks was then implemented in the team's final interactive dashboard.

**During Pandemic Data: EDA, Polarities:** 
Using the code from the Web Scraping Code folder, the team collected during pandemic data for 16 universities. The data is stored in this folder. With the during pandemic data, the team calculated specific mental health keyword frequencies per university, as well as the polarity distributions for each university over a span of 11 months. The word frequency calculations and notebook can be found in a subfolder called Word Frequency Per University. Similarly, the polarity distribution calculations and notebook can be found in a subfolder called Polarities for Each University. The results of both of the notebooks was then implemented in the team's final interactive dashboard.

**Final Interactive Dashboard:**
This folder contains the csvs used in our final interactive dashboard, as well as the notebook containing the interactive graphs. To see the dashboard locally, users can upload the notebook and accompanying csv files into datahub. The notebook has also been deployed to a permanent link using Heroku, and can be found here: http://covid19-social-media-trends.herokuapp.com/


## 🧾 Credits

List of Dependencies:

* [Python 3](https://www.python.org/)
* [Jupyter](https://jupyter.org/)
* [Anaconda](https://www.anaconda.com/)
* [NumPy](http://www.numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [Scikit-Learn](http://scikit-learn.org/stable/index.html)
* [TensorFlow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)


## 📧 Contact us

- 🐬 **Ashritha Eswaran:** aeswaran@berkeley.edu ([LinkedIn])(www.linkedin.com/in/ashritha-e-703aba134)
- 🐶 **Sara Siddiqui:** sarasiddiqui@berkeley.edu (<a href="https://www.linkedin.com/in/sara-sidd">[LinkedIn]</a>)
- 🐯 **Royalle Hurney:** royallehurney@berkeley.edu ([LinkedIn](www.linkedin.com/in/royalle-hurney))
- 🐱 **Helen Zhao:** minyiz0525@berkeley.edu ([LinkedIn](www.linkedin.com/in/arashnourian))


## 🎓 License

[Apache2](https://www.apache.org/licenses/LICENSE-2.0)
