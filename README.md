<a name="readme-top"></a>

<br />
<div align="center">
  <h1 align="center">:japanese_castle: Tower Chat</h1>

  <p align="center">
    <h3>A place where friends can talk with each other.</h3>
    <br />
    <a href="https://github.com/jamesrosal/tower-chat"><strong>Check out the docs »</strong></a>
    <br />
    <br />
    <a href="#about-the-project">View Preview</a>
    ·
    <a href="https://github.com/jamesrosal/tower-chat/issues">Report Bug</a>
    ·
    <a href="https://github.com/jamesrosal/tower-chat/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

![Tower Chat - Authentication](https://github.com/jamesrosal/tower-chat/assets/33856891/a8bd6328-995a-4ca4-b90c-d5fb92969a29)
![Tower Chat - Chat Screen](https://github.com/jamesrosal/tower-chat/assets/33856891/eda204c0-e972-439d-baf3-ef6f14085d87)

Based on the Tower of Babel tale, this is a chat application where you can come together with your friends and just talk. This project was created with the help of chatengine.io and was created for the sole purpose of having a chat component for future projects.

I was recently working on a project for a fashion app that would service apparel development, and this was a component that would help drive the 1-on-1 communication with a professional and a user.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* <img align="left" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="16" /> React
* <img align="left" src="https://cdn.simpleicons.org/express/white" height="16" /> Express
* <img align="left" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="16" /> Node
* <img align="left" src="https://chat-engine-assets.s3.amazonaws.com/temp-logo-min.png" height="16" /> ChatEngine.io

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites
Install the latest npm
* npm
```
npm install -g npm
```

### Installation 
Get the Repository
* In your terminal:
```
cd ~/Desktop
```
* Clone the repo:
```
git clone https://github.com/jamesrosal/tower-chat.git
```
* Change your directory to the repo:
```
cd tower-chat
```

Get your chat API
- Go to https://chatengine.io/, sign up & login.
- In My Projects, click + New Project, name your project and click Create Project (You get one free trial project).
- Go into the Settings of your project, under the Action column. This is where you will copy Project ID & Private Key.
- In the .env file inside the frontend folder, replace PASTE_PROJECT_ID_HERE with your Project ID.
- In the index.js file inside the backend folder, replace PASTE_PRIVATE_KEY with your Private Key.

Dependancies & Running
* In your terminal type: 
```
cd tower-chat
```
* Install dependancies: 
```
npm install
```
* Run the Tower Chat: 
```
npm start
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Profile creation, chat functionality using chatengine.io
- [ ] Password addition for authentication (bcrypt)
- [ ] CRUD functionality for profiles

See the [open issues](https://github.com/jamesrosal/tower-chat/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

James Rosal - [jamesrosal.com](https://jamesrosal.com) - jamesfrosal@gmail.com - [linkedin](https://www.linkedin.com/in/jamesrosal/)

Project Link: [https://github.com/jamesrosal/tower-chat](https://github.com/jamesrosal/tower-chat)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
