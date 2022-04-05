# Guider
Guider is a MERN(Mongodb, Express.js, React.js, Node.js) stack based application for hire tourist guides in Pakistan.

## About the App
  - The main functions that app includes are -
    1. Get Information about a searched city
    2. Hire local guides in a searched city
    3. Browse best tour packages in Pakistan
    4. Guides Authentication using [ Auth0 ](https://auth0.com/)
  - This web app uses
    1. Google Maps Geocoding API (provides geocoding and reverse geocoding of addresses)
    2. Google Maps Places API (returns information about places using HTTP requests)
    3. Stripe API
    4. Travel Advisor API

  - If user wants to hire a guide he/she has to search for a city, after selecting a city(from suggestions) user gets the cost and other information about a guide.
  - After this information user gets a list of local guides which are available in searched city. On the selection of any of the guide it shows all the information about guide- name, hourly charges etc. After this user can put his/her information and your guide will be booked.
  - If user wants to find hotels, attractions or resturants in a searched city, he/she can easily get all of these info just by one single click.
  - This app is free although user can donate if he/she likes. For payments app uses [ Stripe platform ](https://www.npmjs.com/package/@stripe/react-stripe-js)(Npm Package)
  - Local Guides can Sign in/up using G-mail or E-mail/Password.

## In action👀

<h3 align="center">1. Homepage</h3>
<p align="center">
   https://user-images.githubusercontent.com/47333917/161747284-636b1ea2-a14b-4fb8-b777-94f8f3a91407.mp4
 </p> 
 <br>
 <h3 align="center">2. Get Information about Cities </h3>
 <p align="center">
    https://player.vimeo.com/video/696098526?h=c38b26dfd4
</p>
<br><br>
<h3 align="center">3. Payment </h3>
 <p align="center">
    https://user-images.githubusercontent.com/47333917/161747627-a931d436-502c-49de-9059-654d35fce218.mp4
</p>
<br><br>
<h3 align="center">4. Hire a Guide</h3>
 <p align="center">
   https://user-images.githubusercontent.com/47333917/161747612-3ea06a9e-9dfd-446d-82df-9047dc9c09b3.mp4
 </p>
 <br><br>
 
## Some important things to note
   - If you're trying to make changes or to contribute in this project, please make sure you check the .env files in both client and server folders
   - In client/.env file, add Google Maps API key (Restrict with Place API & Geocoding API) and Travel Advisor API key
   - In server/.env file, add Mongodb Atlas cluster url & Stripe secret
   -  That's all!

## Keep Going!!!
   - Feel free to ask your doubts and contribute to this project.
   - Do ⭐ the repo if you like the work!🙌
