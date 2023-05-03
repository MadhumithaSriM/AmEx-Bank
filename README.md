
# AmEx Bank Facial Recognition for transactions or OTP

🌟Submission for American Express Makeathon 2023 🌟




## Instructions to run it locally

1. git clone https://github.com/MadhumithaSriM/AmEx-Bank.git

2. cd ./AmEx-Bank

3. Install node dependencies

4. npm install

5. Replace firebase API keys with your configurations

6. Create a .env file

7. Add relevant credentials (I've given in the last section of Acehacker Final Submission Page)

8. npm start

9. The app is now running at http://localhost:3000/

## Points to remember while testing the app

1. Allow permissions for camera when asked.

2. In case any anything doesnot load it is probably due to server overload, REFRESH the window to solve this.

3. Make sure the URL is starting with https.

4. While sending money to another user make sure you follow the process in sequence as described in the banner on payment page or else it’ll show an error.

5. While doing the Thumbs Up Gesture 👍 on the payment page (for amount less than Rs. 10,000), if the model is not recognizing the gesture, try tilting the hand little bit.


## Research around the Idea

A report suggests that there’s been a massive rise in OTP-related frauds in India, from 880 cases in 2017 to more than 10,000 cases in 2020. Also, many times, OTPs don’t make it to our inbox in time or sometimes don’t arrive at all.

Considering the scale at which digital transactions are happening in India, this is a huge problem, and an alternative should be given to the customer. That’s where our idea comes into the picture.





## The Idea

• Have you also been tired of entering OTP (One Time Password) every time you make any transaction or update any detail on your net banking?

• Do you also sometimes don’t receive OTPs, or do OTPs arrive just after you close the tab?

• I feel the same pain too!

• That’s why, in this American Express Hackathon, I decided to make an Banking Web App that solely relies on Face & Hand posture Recognition technology.

• Here are some functionalities the Web app have -

• Login Process entirely based on your email address and Face Recognition.

• Instead of SMS OTP, every transaction in our web app will be done using hand posture recognition.

• For small-ticket Transactions (less than and equal to 10,000), the user just need to scan the face and then needs to do thumbs up👍 for the transaction to went through and make a victory ✌️ sign for cancelling the transaction.

• For Transactions greater than Rs. 10,000 , the user need to first authenticate by scanning their face and then system will generate a random number and show it on the screen. 

• User just have to posture that number on the screen with help of his fingers.

• Voila! Transaction is done.

• Update your Mobile Phone Number.

• Transaction History to track your spendings.

• Various validation checks to make application more robust

• Mobile Number Format Validation (only accepts Indian Mobile Numbers).

• Payment Type (IMPS/ NEFT/ RTGS) validation based on amount entered (on payment page).

• Prevents user to save a Multi-Face Image (which have more than one person in it).

• Some features that might be implemented next in near future -

• Online KYC using Object Detection and Face Similarity Matching Technology.

• Sentiment/ Mood analysis can also be done to track if a user is willingly doing the transaction or not.

## Tech Stack


• Last but not least, let’s talk about the tech stack I’ll be using to build upon my idea. For the frontend part, I am using React JS mainly and Bootstrap to make it more aesthetic and soothing to the eyes. For Login & Signup Functionality in the backend area, I’ve used Firebase to verify and store the credentials.

• Coming to Face recognition, I am using KAIROS Face API to detect a face in the image (captured through webcam or mobile camera) and also to recognize the face during any authentication process involved.

• Now comes the most exciting stuff, this project will also consume Tensorflow JS and Fingerpose & Handpose library to detect a hand and count fingers raised by the user (needed in Finger-based OTP functionality).



## Libaries Used


• axios : Promise based HTTP client for the browser and node.js

• tensorflow-models/handpose : A palm detector and a hand-skeleton finger tracking model. It predicts 21 3D hand keypoints per detected hand.

• fingerpose : Finger gesture classifier for hand landmarks detected by MediaPipe Handpose. It detects gestures like "Victory" ✌️ or "Thumbs Up" 👍 inside a source image or video stream.

• validator : This library validates and sanitizes strings only. If you're not sure if your input is a string, coerce it using input + ''. Passing anything other than a string will result in an error.

• bootstrap : Bootstrap is a free and open-source CSS framework directed at responsive, mobile-first front-end web development. It contains HTML, CSS and JavaScript-based design templates for typography, forms, buttons, navigation, and other interface components.

• react-bootstrap : React-Bootstrap is a component-based library that provides native Bootstrap components as pure React components.

• react-countdown : A customizable countdown component for React

• react-number-format : React component to format number in an input or as a text

• react-webcam : Webcam component for React to access webcam and campture images and videos



## Documentation

[Ideation Document](https://docs.google.com/document/d/1vjnRXz1xJc0t0TuXG265XJB6qwfX4Nt2IopFpPfGLL4/edit?usp=sharing)


## 🔗 Connect with me

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/madhumitha-sri-m-9b0111210/)



