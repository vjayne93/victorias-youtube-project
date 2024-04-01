## victorias-youtube-project
This code is adapted from https://github.com/mCodingLLC/mCodingYouTube. My project is for educational purposes.
My code is full of redundencies and poor technique, but it works. I am thirteen weeks into a data analysis boot camp as of commiting this. 

### How to Use This Code
This code runs in Jupyter Notebooks. To run this code, you need to have the following installed to your terminal:
* python-dotenv
* google-api-python-client
* google-auth
* google-auth-oauthlib
* google-auth-httplib2
* pytest

Create a project in Google Developer Cloud: https://console.cloud.google.com/cloud-resource-manager

Add the Youtube Data API v3 to your Project
![image](https://github.com/vjayne93/victorias-youtube-project/assets/152992214/3714df63-1373-46ad-becc-cc603ce4c0df)

Add yourself as a test user under APIs & Services
![image](https://github.com/vjayne93/victorias-youtube-project/assets/152992214/9c1910c9-89d7-4ea1-82f9-2f09cdfb9abd)

In the API & Services section of the project, download the OAuth 2.0 Client IDs to a "secret_client_file.json" in your directory.
![image](https://github.com/vjayne93/victorias-youtube-project/assets/152992214/59b1b31f-507b-476b-9408-cc34ecef054c)

Go to the "credentials" section of the APIs & Services and add http://localhost:8080/ as an Authorized redirect URIs
![image](https://github.com/vjayne93/victorias-youtube-project/assets/152992214/91856fe5-9b72-4101-ae48-22aa6cf6ec59)
