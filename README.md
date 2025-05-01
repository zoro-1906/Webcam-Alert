# Project Name : MotionAlert

## What the project does:
Captures video through a webcam using OpenCV.

Detects motion in real-time from the video feed.

Saves snapshots when significant movement is detected.

Automatically sends an email with the captured image attached.

Periodically deletes old images from the storage folder.

Utilizes multithreading to handle:

Email sending.

Folder cleanup.

Ensures smooth and non-blocking video processing.

## Why the project is useful:
Motion Detection: Detects motion in real-time using a webcam feed and highlights moving objects — ideal for security applications.

Automated Alerts: Captures an image upon detecting motion and sends an email alert with the snapshot to notify the user immediately.

Background Processing: Utilizes multithreading to handle email notifications and folder cleanup without interrupting motion detection.

Efficient Resource Management: Automatically cleans up old image files to prevent disk space issues and maintain smooth system performance.

## How users can get started with the project:
1. Clone the repository:
https://github.com/zoro-1906/Webcam_Alert.git
cd motion-detection-email-notifier

3. Install the necessary dependencies:
You'll need Python, OpenCV, and a few other libraries. Run the following command to install them:
pip install opencv-python streamlit

3. Set up your email credentials:
The send_email function (in the emailing.py module) will require your email credentials to send the alerts. Update the function with your email settings. Ensure you use an app-specific password for Gmail (or similar services).

4. Prepare folder structure:
Create a folder named images to store the captured images:
mkdir images

5. Run the script

6. If you encounter any issues or have questions about the project, you can:
Open an issue: If you find a bug or need help with something specific, feel free to open an issue on the project's GitHub page.
