# PythonDataScienceFullThrottle
Downloads for my [Safari Online Learning](https://learning.oreilly.com) live training course **Python Data Science Full Throttle: Introductory Artificial Intelligence (AI), Big Data and Cloud Case Studies**

# Setting Up a Custom Conda Environment
These are the actual commands I used to set up a fresh environment last week:
 
* This creates a custom environment named pydsftjuly21—you can choose any name  you like:
 
'''
conda create --name pydsftjuly21
'''

* This activates the environment you just created—change the name if you used a different name above:

'''
conda activate pydsftjuly21
'''

* The following two commands install most of what you need for the content from ch11, ch12, ch13, ch14, ch15 and a good chunk of ch16 that I covered yesterday—if you’re working from our books or videos, you might need to subsequently install a few other packages:
 
'''
conda install jupyterlab nodejs ipympl textblob wordcloud spacy tweepy geopy folium scikit-learn tensorflow matplotlib seaborn pymongo dnspython numpy pandas imageio pyaudio pydub
 
pip install dweepy pubnub ibm-watson tweet-preprocessor
'''
 
The pip command above is needed because a few packages are not available through the conda repository.
 
The YML files sometimes work and sometimes don’t. I created that quickly yesterday from my Mac and it could well include stuff that’s Mac specific.

# Past Course Links (accessible only if you were registered for that course)
July 27, 2021: https://learning.oreilly.com/attend/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920289197/0636920056748/

June 22, 2021: https://learning.oreilly.com/attend/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920289197/0636920054946/

May 25, 2021: https://learning.oreilly.com/attend/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920289197/0636920054006/

April 27, 2021: https://learning.oreilly.com/attend/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920289197/0636920052503/

February 23, 2021: https://learning.oreilly.com/live-training/courses/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920051482/

January 19, 2021: https://learning.oreilly.com/live-training/courses/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920474654/

December 8, 2020: https://learning.oreilly.com/live-training/courses/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920506140/

November 17, 2020: https://learning.oreilly.com/live-training/courses/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920464198/

October 20, 2020: https://learning.oreilly.com/live-training/courses/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920404613/

September 29, 2020: https://learning.oreilly.com/live-training/courses/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920410720/

August 18, 2020: https://learning.oreilly.com/live-training/courses/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920457855/

July 28, 2020: https://learning.oreilly.com/live-training/courses/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920444305/

June 16, 2020: https://learning.oreilly.com/live-training/courses/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920436126/

May 19, 2020: https://learning.oreilly.com/live-training/courses/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920389675/

March 17, 2020: https://learning.oreilly.com/live-training/courses/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920373117/

January 21, 2020: https://learning.oreilly.com/live-training/courses/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920358213/

December 17, 2019: https://learning.oreilly.com/live-training/courses/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920322481/

August 26, 2019: https://learning.oreilly.com/live-training/courses/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920305996/

July 30, 2019: https://learning.oreilly.com/live-training/courses/python-data-science-full-throttle-with-paul-deitel-introductory-artificial-intelligence-ai-big-data-and-cloud-case-studies/0636920289173/


I'll keep this repository up-to-date with any changes I make for future presentations. 

**These files are for your personal use and may not be redistributed or reposted.**

If you have any questions, open an issue in the Issues tab or email us: deitel at deitel dot com.

Copyright 2019 by Deitel & Associates, Inc. and Pearson Education, Inc. All Rights Reserved. 

# Setup for Executing the Examples
The notebooks contain links to my videos and book on safari where I discuss setup issues. 

# Our Books on Which These Examples Are Based
The content of this course is based on our book <a href=https://amzn.to/2Kd8dQk target="_blank">Python for Programmers</a>, which is a subset of our book <a href=https://amzn.to/2KfCptN target="_blank">Intro to Python for Computer Science and Data Science: Learning to Program with AI, Big Data and the Cloud.</a>
   
![Cover image for Python for Programmers](https://deitel.com/wp-content/uploads/2020/01/python-for-programmers.jpg)

The authors and publisher of this book have used their best efforts in preparing this book. These efforts include the development, research, and testing of the theories and programs to determine their effectiveness. The authors and publisher make no warranty of any kind, expressed or implied, with regard to these programs or to the documentation contained in this book. The authors and publisher shall not be liable in any event for incidental or consequential damages in connection with, or arising out of, the furnishing, performance, or use of these programs.
