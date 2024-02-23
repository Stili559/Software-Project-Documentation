<div align="center">
<img src="https://github.com/Stili559/Software-Project-Documentation/assets/80035053/3fa9179c-13e9-4359-b7da-62beb7ef2e5d">
</div>

# Music Library
  
## Overview

**Music Library** is an interactive front-end application designed to simplify the process of curating and managing a personal collection of **music albums**. It serves as a Single Page Application **(SPA)** that facilitates seamless user experiences for album curation.

## Vision and Mission

Our vision and mission is to revolutionize the way music lovers interact with their collections by providing a platform that is not only user-friendly but also a central hub for music discovery and library management. We aspire to create a vibrant community of music enthusiasts who contribute to the richness of our music library.

<p align="center">
  <img src="https://img.shields.io/badge/Language-HTML%20%7C%20CSS%20%7C%20Node.js%20%7C%20Express.js%20%7C%20Chai%20%7C%20Mocha-blue?style=flat-square">
</p>

<p align="center">
 <img src="https://github.com/Stili559/Software-Project-Documentation/assets/80035053/433b8697-b5c4-43c9-91a4-18a630208371">
</p>

## Key Functionalities

- **Album Browsing**: Dive into a comprehensive library of music albums.
- **Secure Registration**: Sign up with ease using an email and password system.
- **Album Personalization**: Create your own album cards with personalized details.
- **Direct Content Management**: Edit or remove your contributions at your discretion.

## How to access the application 
### Step 1: Clone the repository

```shell
https://github.com/Stili559/Software-Project-Documentation.git
```

### Step 2: Install the the required resources

```shell
npm install
```

### Step 3: Run the project

```shell
npm start
```

## How to access the API
### Open the link when the project is started locally

```shell
http://localhost:3300/api-docs
```

### The following API endpoints are available for interacting with the application

- `GET /api/albums?order=release_date&dir=desc` - Retrieves a list of albums, sorted by release date in descending order.
- `GET /api/albums/{albumId}` - Fetches details for a specific album using its unique identifier.
- `POST /api/albums` - Adds a new album to the collection. Requires a JSON payload with album details. Example payload: `{ "artist": "John Doe", "title": "New Horizons", "coverUrl": "https://example.com/new_horizons_cover.jpg", "releaseDate": "June 1, 2024", "recordLabel": "Indie Sounds", "sales": "500,000 copies" }`.
- `PUT /api/albums/{albumId}` - Updates an existing album's details. Send a complete JSON payload with all album details, including any changes. Example payload mirrors the POST endpoint.
- `DELETE /api/albums/{albumId}` - Removes an album from the collection using its unique identifier.
- `POST /api/users/authenticate` - Authenticates a user and returns a session token. Requires a JSON payload with user credentials. Example payload: `{ "username": "user123", "password": "securepassword" }`.

  ![image](https://github.com/Stili559/Software-Project-Documentation/assets/80035053/2e8620f3-37e6-488c-ac4c-bf9972d78fc7)

## Unit Tests
The Music Library is equipped with a suite of unit tests designed to ensure the reliability and stability of the application. These tests cover a range of functionalities, from user authentication to album management.

#### Running Tests

To run the unit tests for the Harmony Hub application, follow these steps:

1. Open the terminal in visual studio code
2. Type in "npm run test"
3. After few seconds different test will appear in the terminal

![image](https://github.com/Stili559/Software-Project-Documentation/assets/80035053/352fd3cd-c9fc-428a-b78b-dae7576224b5)

## Home Page

The Home Page of the Music Library serves as the landing space for all visitors. 

![image](https://github.com/Stili559/Software-Project-Documentation/assets/80035053/606ba46c-2811-433e-92b9-8702fffc87e8)

## Login Page

Our Login Page offers a secure entry point for returning users. It's designed with simplicity in mind, requiring just an email and password.

![image](https://github.com/Stili559/Software-Project-Documentation/assets/80035053/75c3324c-7675-4a1d-adb2-d484c9e17dbb)

## Register Page

The Register Page is the gateway for new users to join the Music community. It requires new members to provide an email address and create a password. Once registered, users can start creating, managing, and sharing their album collections.

![image](https://github.com/Stili559/Software-Project-Documentation/assets/80035053/2c7b34fb-5cfb-42f5-9cf8-8474f0484487)

## Dashboard

For users who have logged in, the Dashboard is the control center of their music library experience. Here, users can view their curated albums, access management tools to edit or delete their entries, and see personalized recommendations. 

![image](https://github.com/Stili559/Software-Project-Documentation/assets/80035053/92434afe-cc8e-4e1f-8f11-4257ba6c68da)

## Add Album
The Add Album feature is a central component of the Harmony Hub Music Library. It allows registered users to contribute new albums to the library.

![image](https://github.com/Stili559/Software-Project-Documentation/assets/80035053/cbaad971-4775-4f03-bbb4-573b1a3a04e1)

