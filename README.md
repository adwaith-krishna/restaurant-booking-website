# Restaurant Booking Website
The restaurant booking website is build on Shaif's Cuisine by Rana Rabees.The site enables the customer to book table,order food adn to give feedback.Admin can view the booking and the feedback.Chef can view the orders.


![Screenshot 2024-05-16 232439](https://github.com/adwaith-krishna/restaurant-booking-website/assets/61908327/bdf07590-4259-422d-a690-50170dbc1b0c)


## Features
### Customer Panel
* Customer can book table.
* Customer can order food and pay the bill.
* Customer can give feedback.
### Admin Panel
* Admin Login.
* Can view table bookings.
* Can view the feedbacks.
### Chef Panel
* Chef Login.
* Can view the orders.




## Getting Started
1. Clone the repository:
```console
git clone https://github.com/your-username/college-placement-portal.git
```


2. Go to [firebase](https://firebase.google.com/) and choose firestore and authentication.Then copy the config and update it in the code.
```js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

3. Go to [Stripe](https://stripe.com/in) and create a test account then replace the link with you template link if you want to include Payment.
```js
window.location.href = 'YOUR_LINK';
```







## Tech Stack
* Frontend: HTML, CSS, JavaScript
* Backend: JavaScript
* Database: Firestore
* Authentication: Firebase Authentication




## Acknowledgements
* This project was developed as a college mini project.
* I do understand that it is a basic one and may have many flaws in it.
* This project is build on [Shaif's Cuisine](https://github.com/RanaRabees/Shaif-S-Cuisine.git).
