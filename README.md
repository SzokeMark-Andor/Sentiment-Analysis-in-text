# **Sentiment Analysis App**

## **Overview**

This Python application provides a graphical user interface (GUI) for sentiment analysis of text data. It incorporates sentiment analysis using TextBlob, MySQL for storing sentiment data, and fetching reviews from Google Play. The application is built with PyQt5 for the GUI.

## **Requirements**

Ensure you have the required Python packages installed. You can install them using the following command:
```bash
pip install -r requirements.txt
```

Make sure you have the necessary dependencies installed for PyAudio:
On Ubuntu, you may need to run:
```bash
sudo apt-get install portaudio19-dev
```
On macOS, you can use Homebrew:
```bash
brew install portaudio
```
## **Configuration**

The database connection details are specified in the config.ini file:
```bash
[database]
host = #Write here your database host name
user = #Write here your database username
password = #Write here your database password
dbname = #Write here your database name
```
Please ensure that the configuration file is properly configured with the correct database credentials.

## **Usage**

To run the application, execute the following command:
```bash
python your_app_filename.py
```
Replace your_app_filename.py with the actual filename of your Python application.

## **Features**

-Text Sentiment Analysis: Analyze the sentiment of text input using TextBlob and categorize it as 'Happy,' 'Sad,' 'Neutral,' 'Excited,' or 'Angry.'

-Google Play Reviews: Fetch and analyze reviews for a given Google Play app package name.

-Voice Input: Utilize speech recognition to convert voice input into text for sentiment analysis.

-Plot Sentiment Counts: Visualize sentiment counts using matplotlib.

## **Styling**

The application GUI is styled using a stylesheet defined in the code for consistent and visually appealing design.

## **Database Interaction**

The application interacts with a MySQL database to store and retrieve sentiment data. Ensure the database connection details in config.ini are accurate.

## **Issues and Contributions**
If you encounter any issues or have suggestions for improvements, please open an issue on the GitHub repository. Contributions are welcome!

## **License**
This project is licensed under the MIT License.
