## Fake News Detection System
 ![home](https://imgur.com/03BRS1u.png)
 


## Let's enhance the digital literacy and critical thinking in today's information-driven society

#### INTRODUCTION


* The Clickbait Fake News Detection System is a web-based application designed to analyze and identify clickbait articles from various sources. With the increasing spread of misinformation and sensationalized content, this system aims to provide users with a reliable tool to distinguish between genuine news and clickbait.

* The project leverages machine learning techniques and natural language processing algorithms to detect patterns and characteristics commonly associated with clickbait articles. By analyzing the article's content, headline, and other relevant factors, the system provides a prediction of whether the article is likely to be clickbait or not.
The system's user-friendly interface allows users to submit articles for analysis and receive real-time results. Additionally, users can provide feedback on the accuracy of the system's predictions, which helps improve its performance over time.

* By utilizing advanced technologies and algorithms, the Clickbait Fake News Detection System aims to assist users in making informed decisions about the credibility and reliability of the news articles they encounter online. The project not only addresses the challenges of combating clickbait but also contributes to the larger goal of promoting digital literacy and critical thinking in today's 
information-driven society.  

* Overall, the Clickbait Fake News Detection System is a valuable tool that empowers users to navigate the online news landscape with confidence and trust in the authenticity of the information they consume.

- **Deployed site** <[deployed website](https://stoicism-sympathei.github.io/Fake-News-Detection-System/)>
- **Blog article** <[blog post](https://medium.com/@mogesanonymous/fake-news-detection-system-79b858ec4f4e)> 
## ⚠ This project is on progress is not completed yet it just prototype 
## Table of Content
* [Installation](#installation)
* [Usage](#usage)
* [Authors](#authors)
* [License](#license)

## Installation
-	**Set up the Server**
*	Ensure that you have a server or hosting environment with a compatible operating system (e.g., Ubuntu, CentOS) and necessary configurations (e.g., web server, database server).
- **Install Required Software**
*	Install Python: Check if Python is already installed on the server by running `python3 --version`. If Python is not installed, install it using the appropriate package manager for your operating system.
*	Install Django: Run `pip3 install django` to install Django, the Python web framework.
*	Install `Node.js` and `npm`: Follow the official `Node.js` installation guide to install `Node.js` and `npm`, which will be needed for frontend dependencies and build processes.
- **Configure the Database**
*	install a database management system `MySQL` on your server.
*	Configure Django's database settings in the `settings.py` file of your project to connect to the database.
-	**Clone the Project**
*	Use a version control system (e.g., Git) `git clone "git@github.com:stoicism-sympathei/Fake-News-Detection-System.git"`.
-	**Install Project Dependencies**
*	Backend: Navigate to the project directory and run `pip3 install -r requirements.txt` to install the required Python libraries and dependencies listed in the requirements.txt file.
*	Frontend: Navigate to the frontend directory within the project and run npm install to install the necessary frontend dependencies.
-	**Build the Frontend Assets**
*	In the frontend directory, run npm run build to build the frontend assets and generate the static files.
- **Run Database Migrations**
*	Apply database migrations to set up the necessary database tables by running `python3 manage.py` migrate in the project directory.
- **Collect Static Files**
*	Run `python3 manage.py` collectstatic to collect static files into a single directory.
- **Configure Web Server**
*	Set up a web server `Nginx` to serve the static files and proxy dynamic requests to the Django backend.
*	Configure the web server to forward requests to the Gunicorn WSGI server, which will run the Django application.
- **Start the Application**
*	Start the Gunicorn server by running `gunicorn clickbait_fake_news_detection_system.wsgi` in the project directory.
*	Configure the Gunicorn server to run as a background process or use process management tools like Supervisor or systemd.
-	**Test the Deployment**
*	Access your Clickbait Fake News Detection System application through the server's IP address or domain name in a web browser.
*	Verify that the application is running and functioning correctly.

## Usage
- **Open a web browser** 
*  Launch a web browser of your choice on your device (e.g., Chrome, Firefox, Safari).

- **Enter the URL** 
* In the address bar of the web browser, enter the URL of the Clickbait Fake News Detection System. This could be the domain name or IP address associated with the server where the project is deployed.

- **Navigate to the homepage**
*  Once the web page loads, you will typically land on the homepage of the Clickbait Fake News Detection System. This page provides an overview of the system and its features.

- **Explore the features** 
*  Use the navigation menu or buttons provided on the webpage to access different sections and features of the application. For example, you will find sections like `Introduction`, `Features`, `Application`, `Article Submission Form`, or `uer Feedback`.

- **Submit articles for analysis** 
* the application includes an article submission form, you can fill out the required information, such as the `article title`, `content`, and `source`, and `submit` it for analysis. The system will then process the article and provide a detection result indicating whether it is clickbait or fake news.

![news article](https://imgur.com/rWj6bLO.png)

- **Provide user feedback** 
* you can provide your thoughts or opinions on the detection results or the overall system. This may involve rating the accuracy of the system's analysis or leaving comments.

- **Interact with other features** 
*  Depending on the specific features implemented in the Clickbait Fake News Detection System, you will have additional options to explore. This could include viewing `real-time analysis`, `accessing user-friendly interfaces`, or exploring other functionalities provided by the system.

- **Follow instructions and prompts** 
* Throughout your interaction with the application, follow any instructions or prompts provided on the screen. These may guide you on how to use specific features, provide input, or interpret the results.

- **Repeat steps as needed** 
* You can repeat the process of `submitting articles`, `exploring features`, and `providing feedback` as needed. The application will provide a user-friendly interface and clear instructions to facilitate your interaction.

## Authors
 **Moges Amane**
* [Github](https://github.com/stoicism-sympathei)
* [Linkedin](https://www.linkedin.com/feed/)
* 📧[Email](https://mogesanonymous@gmail.com)
   


## License
Public Domain. No copy write protection at this point of time.




