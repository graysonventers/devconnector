## Built via Travery Media MERN Stack course
<br>

# Quick Start
## Add a default.json file in config folder with the following
> { <br>
    "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>", <br>
  "jwtSecret": "secret", <br>
  "githubToken": "<your_secrect_access_token>" <br>
}

## Install server dependencies
> npm install
## Install client dependencies
> cd client
npm install
## Run both Express & React from root
> npm run dev
## Build for production
> cd client
npm run build