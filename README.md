<div id="top"></div>


<!-- PROJECT LOGO -->
<br>
<div align="center">
  <a href="https://github.com/CHI-Discord-Bot/discord-bot">
    <img src="https://raw.githubusercontent.com/CHI-Discord-Bot/CHI-Discord-Bot.github.io/main/images/ChaHaeIn.jpg" alt="Logo" width="200" height="200">
    <h1 style="color: black">Cha Hae-In</h1>
  </a>

  <h3 align="center">A discord bot with a lot of cmds and functions.</h3>

<!-- Shields -->
  <div align="center">
    <img src="https://img.shields.io/github/license/CHI-Discord-Bot/discord-bot?style=flat-square">
    <img src="https://img.shields.io/github/issues/CHI-Discord-Bot/discord-bot?style=flat-square">
    <img src="https://img.shields.io/github/contributors/CHI-Discord-Bot/discord-bot?style=flat-square">
  </div>

  <p align="center">
    <br />
    <a href="https://github.com/CHI-Discord-Bot/discord-bot/issues">Report Bug</a>
    ·
    <a href="https://github.com/CHI-Discord-Bot/discord-bot/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- GETTING STARTED -->
# Getting Started
First of all, thanks for showing interest in this discord bot! We aim to provide a multifunctional discord bot.
Have fun exploring it.

To get a copy up and running follow these simple steps. 

## Installation

1. Fork this repository.

2. Head over to [Heroku](https://www.heroku.com/) and create an account. It's completely free.

    * This project is optimized for hosting on [Heroku](https://www.heroku.com/).

3. Create a new application on [Heroku](https://www.heroku.com/)

4. Deploy this project to your [Heroku](https://www.heroku.com/) app. 

    * To do so, head over to the deploy category and select the GitHub deploy method. Then select the repository you just forked and deploy the main branch. 

5. In the settings of the app you need to add a few env vars. Add the following env vars.
    ```
    BOT_TOKEN = your bot token
    ```

6. Head over to your [Heroku](https://www.heroku.com/) app settings and add the following buildpacks.

    - [ffmpeg buildpack](https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest): This is necessary to use the music commands
    - [opus](https://github.com/xrisk/heroku-opus): This is also necessary for the music commands
    - python: Just select this by clicking the add buildpack button

    Make sure that the python buildpack is at the bottom of the buildpacks.

7. Now the discord bot is ready to host. Head over to the resources tab and switch the worker from off to on.

<p align="right"><a href="#top">back to top</a></p>



<!-- CONTRIBUTING -->
# Contributing

Any contributions you make are **greatly appreciated**.

If you have any suggestions and want to take action yourself, please fork the repo and create a pull request. 
You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

Please make sure to read the [Contributor Guidelines](https://github.com/CHI-Discord-Bot/discord-bot/blob/main/.github/CONTRIBUTING.md)

<p align="right"><a href="#top">back to top</a></p>



<!-- LICENSE -->
# License

Distributed under the [GNU v3.0](LICENSE) License. See `LICENSE` for more information.

<p align="right"><a href="#top">back to top</a></p>



<!-- CONTACT -->
# Contact

[PolarBear4u](https://polarbear4u.github.io/) - PolarBear4u#7025

[Frozen0wl](https://github.com/Frozen0wl) - Frozen0wl#9220

<p align="right"><a href="#top">back to top</a></p>

