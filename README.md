#expressions.github.io
# Face Recognition
This web app has been built as a submission for the Microsoft Engage Mentorship(Face Recognition) Challenge. The Face-Detection uses [Face API](https://justadudewhohacks.github.io/face-api.js/docs/index.html), which is a JavaScript API for real-time face detection. This also implements facial landmark detection, along with Face Expression Recognition (for example: sad, angry, happy, surprised).
## Installation
* **[Download and install node.js](https://nodejs.org/en/)**
* **Next install NPM's live server**
```bash
npm install -g live-server
```
**We may also install live-server in VSCode by going to extensions, searching for live
server and installing the same.**
* **Clone this repository and open the same in VSCode**

## About
The HTML page **index.html** uses the Face API to detect faces and expressions. A number on the top of the face represents the probability that the object is in fact a face. However, since opening a webcam may require some privacy, a startup page **Start.html** has been created so that one can decide when they are ready to use their webcam device.

## Usage
Open the folder in vscode. Right-Click on **Start.html** and choose *Open in live server*.
Alternatively, we can do 
```bash
cd /project-directory
live-server 
```
When you're ready to turn your web camera on for real-time Face Recognition, Click on the orange button at the bottom. 

## Acknowledgement
My mentor Yash was a huge help and as this was built during my final exams, interaction with him during the meetings motivated me to finish the project.  
