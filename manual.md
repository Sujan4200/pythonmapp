# Flask Audio Player App User Manual

## Introduction

The Flask Audio Player App is a web application that allows users to play audio files stored on Amazon S3. Users can sign in to the app and play the audio files they have subscribed to. The app features a blue light theme color for a visually pleasing experience.

## Installation

To use the Flask Audio Player App, you need to follow these steps:

1. Install Python: Make sure you have Python installed on your system. You can download Python from the official website: [https://www.python.org/downloads/](https://www.python.org/downloads/)

2. Clone the repository: Clone the repository containing the Flask app code to your local machine.

3. Set up AWS S3 credentials: Open the `main.py` file and replace the placeholders for AWS access key ID, secret access key, and bucket name with your own credentials. These credentials are required to access the audio files stored on Amazon S3.

4. Install dependencies: Open a terminal or command prompt and navigate to the directory where the Flask app code is located. Run the following command to install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

## Usage

To use the Flask Audio Player App, follow these steps:

1. Start the Flask app: In the terminal or command prompt, navigate to the directory where the Flask app code is located. Run the following command to start the app:

   ```
   python main.py
   ```

2. Access the app: Open a web browser and enter the following URL: [http://localhost:5000/](http://localhost:5000/)

3. Sign in: Click on the "Login" link to access the login page. Enter your username and password, then click the "Login" button.

4. Dashboard: After successful login, you will be redirected to the dashboard page. The dashboard displays a list of audio files that you have subscribed to.

5. Play audio: Click on the name of an audio file in the dashboard to play it. The audio player will appear, and you can control playback using the controls provided.

## Customization

If you want to customize the theme color of the app, you can modify the `style.css` file. Open the file and locate the following line:

```
body {
    background-color: #00BFFF; /* Blue light theme color */
    color: #FFFFFF;
    font-family: Arial, sans-serif;
}
```

You can change the value of `background-color` to any valid CSS color code to customize the theme color.

## Conclusion

The Flask Audio Player App provides a convenient way to play audio files stored on Amazon S3. By following the installation and usage instructions in this user manual, you can easily set up and use the app. Enjoy your music playback experience with the blue light theme color!