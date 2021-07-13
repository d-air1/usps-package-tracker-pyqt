# usps-package-tracker-pyqt
An basic bare-bones Qt app that scrapes information from the USPS website after receiving a tracking number from the user.

 In the future, I might investigate if the usps has an api that I can make use of. This project actually started with me wanting to use python to get my own tracking information from usps without having to open a browser and go to the website every time. Soon after I also became interested in the Qt framework. I was having a hard time coming up with an idea to use for an Qt app, so I decided to revisit one of my old projects which was the usps website scraper I had written in python.

<h3>To make into a stand alone executable you can:</h3>
After cloning this repo<br><br>
pip install --user pyinstaller<br>
pyinstaller usps-pyqt
