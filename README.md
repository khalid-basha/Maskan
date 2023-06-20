# Maskan
Maskan is a real estate platform designed to provide a trusted user-friendly experience for buying and selling properties in the Palestinian market. Our goal is to address the limitations of previous attempts and offer comprehensive features that cater to the diverse needs of our users.

As a buyer on Maskan, you have access to a wide range of properties listed for sale. You can easily navigate through the available options using advanced search filters, including price, location, and number of rooms, among others. Our platform allows you to view 360 images, and read detailed property descriptions and features.

If you find a property that you’re interested in, Maskan provides the convenience of scheduling a tour. You can arrange a visit to personally inspect the property and get a closer look. Additionally, our platform offers a built-in chatting system, allowing you to easily communicate with the property owner or seller, in addition to getting notified whenever needed such as a property you own has a new reserved visit.

Moreover, Maskan incorporates a machine learning system that provides price predictions based on the house features. This technology takes into account various factors such as property size, location, room number, and market trends to estimate the fair market value of a property. This feature assists buyers and sellers in considering the pricing of properties.

From an administrative perspective, Maskan ensures quality control by allowing administrators to review and manage seller requests. This way, we maintain the integrity and reliability of the listings displayed on our platform.

At Maskan, we are committed to serving as a comprehensive real estate solution in the Palestinian market. Our platform aims to address the gaps observed in previous initiatives by offering a range of features that align with the diverse needs of our users. Whether you are looking to buy or sell a property, our machine learning system, combined with our user-friendly interface, will assist you in making well-informed decisions.

## Requirements
- ReacJS 18.2.0.
- React-native 0.71.7.
- Node.JS 18.14.1.
- Python 3.8.
- pip .
- Django 4.1.7.
- npm 9.3.1.
Other packeges and librarys will mentions later.

## Installation

### Prerequisites

Make sure you have the following software installed on your machine:

- Node.js.
- npm.
- Python.
- pip.

### Steps

1. Clone the repository.
```
git clone https://github.com/khalid-basha/Maskan.git
```
2. Install the required dependencies for the server-side:
```
cd Maskan-backend
pip install -r /requirements.txt
```
  Run migrations to create the database and tables
```
python3 manage.py makemigrations
python3 manage.py migrate
```
  Create a superuser to access the admin panel
```
python manage.py createsuperuser
```
  Start the development server
```
python manage.py runserver
```
3. Install the required dependencies for the web application:
```
cd Maskan-frontend
npm install --force
```
  Start the development server.
```
npm start
```
Open your browser and navigate to [http://localhost:3000](http://localhost:3000).

4. Install the required dependencies for the mobile application:
```
cd Maskan-mobile
npm install
```
  Start the development server
  ```
  npm start
  ```
  use expo Go mobile application to scan the QR code shown on terminal.
  
## Contributing
To contribute to the project, follow these steps:

1. Fork the repository and clone it to your local machine.

2. Create a new branch for your changes.

3. Make the changes and commit them to your branch.

4. Push the branch to your forked repository.

5. Create a new pull request against the main repository.

## References
* Python 3.8 Documentation. from https://www.python.org/downloads/release/python-380/
* React Documentation. from https://react.dev/
* Expo Documentation. from https://docs.expo.dev/
* Google Maps platform Documentation. from https://developers.google.com/maps/get-started
* Push notifications in expo. from https://docs.expo.dev/push-notifications/overview/
* React Native Documentation. from https://reactnative.dev/docs/getting-started
* Django Documentation. from https://docs.djangoproject.com/
* Django rest-framework Documentation. from https://www.django-rest-framework.org/
* AWS Documentation. from https://docs.aws.amazon.com/
* Axios Documentation.  from https://axios-http.com/docs/intro
* Material-UI Documentation. from https://mui.com/material-ui/getting-started/overview/
* Postgresql Documentation. from https://www.postgresql.org/docs/


