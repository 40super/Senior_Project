# Senior_Project
My coding project uses a machine learning algorithm to help determine if a URL at face
value be malware or not. In other words, when given an URL, the machine learning algorithm
determines based on the address provided if it could be malware or not. The first step on
developing a program to detect if a URL is malicious is by gathering data. By using a web
scraper which is a program that goes through a website and gather information, you can store
that data onto a file for it to be analyzed. In this case, I scraped data from a virus database called
vxvault.com which has thousands of entries that are viruses and imported it onto a csv sheet
which then was cleaned for URL only. On the other hand, I had trouble finding a database of
clean website but found an existing data sheet that had a list of clean websites and used that to
mix with the malicious website. Additionally, once all the data was scraped and imported into
the csv, there was a total of 72000 website entries used for the algorithm. Once the data was
cleaned properly, the next step was to create the malware detection algorithm which uses a
specific algorithm called logistic regression. The article “Using Machine Learning To Detect
Malicious URLS” by Faizan Ahmad teaches user how to create an algorithm to detect malicious
URL in which I used to help create the program. Logistic regression is used to find relationship
of a binary variable with the independent variable which in this case was the websites and if they
were either malicious or clean. The algorithm then had to be trained and tested in which in this
case was trained on 80% of the data while 20% of the data it was tested on. As a result, the
algorithm performed with a 99% accuracy which is significant. When given random website like
“www.facebook.com” it can tell the URL from face value is clean which can be useful in many
ways. The use of this program when browsing through the web can give you insight if a website
has the potential of being dangerous or not before anything is downloaded onto the computer.
This one of many examples of how the use of machine learning can benefit the cybersecurity
field and with the right implementations, the cybersecurity field can progress and create more
complex protection algorithms that can be difficult for adversaries to break.

This is a sample result when given a list of website links where the algorithm will then determine at face value if it can be malicious or not.
![SampleResult](https://user-images.githubusercontent.com/1377891/155343775-781af063-6186-4e37-9068-1dc631189a80.PNG)
