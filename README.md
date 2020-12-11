<p align="center">
    <a href="https://github.com/MadhavReddy672">
        <img src="resources/userge.jpg" alt="thunders">
    </a>
    <br>
    <b>Powerful Telegram UserBot</b>
    <br>
    <a href="https://github.com/UsergeTeam/Userge#inspiration-">Inspiration</a>
    &nbsp•&nbsp
    <a href="https://github.com/UsergeTeam/Userge#features-">Features</a>
    &nbsp•&nbsp
    <a href="https://github.com/UsergeTeam/Userge#example-plugin-">Example</a>
    &nbsp•&nbsp
    <a href="https://github.com/UsergeTeam/Userge#requirements-">Requirements</a>
    &nbsp•&nbsp
    <a href="https://github.com/UsergeTeam/Userge#project-credits-">Project Credits</a>
    &nbsp•&nbsp
    <a href="https://github.com/UsergeTeam/Userge#copyright--license-">Copyright & License</a>
</p>

# Thunder Bot 🔥

[![Build Status](https://travis-ci.com/UsergeTeam/Userge.svg?branch=alpha)](https://travis-ci.com/UsergeTeam/Userge)
![Python Version](https://img.shields.io/badge/python-3.8-lightgrey)
![Release](https://img.shields.io/github/v/release/UsergeTeam/Userge)
![Stars](https://img.shields.io/github/stars/UsergeTeam/Userge)
![Forks](https://img.shields.io/github/forks/UsergeTeam/Userge)
![Issues Open](https://img.shields.io/github/issues/UsergeTeam/Userge)
![Issues Closed](https://img.shields.io/github/issues-closed/UsergeTeam/Userge)
![PRs Open](https://img.shields.io/github/issues-pr/UsergeTeam/Userge)
![PRs Closed](https://img.shields.io/github/issues-pr-closed/UsergeTeam/Userge)
![Contributors](https://img.shields.io/github/contributors/UsergeTeam/Userge)
![Repo Size](https://img.shields.io/github/repo-size/UsergeTeam/Userge)
![License](https://img.shields.io/github/license/UsergeTeam/Userge)
![Commit Activity](https://img.shields.io/github/commit-activity/m/UsergeTeam/Userge)
[![Plugins Repo!](https://img.shields.io/badge/Plugins%20Repo-!-orange)](https://github.com/UsergeTeam/Userge-Plugins)
[![Join Channel!](https://img.shields.io/badge/Join%20Channel-!-red)](https://t.me/theUserge)
[![DeepSource](https://static.deepsource.io/deepsource-badge-light-mini.svg)](https://deepsource.io/gh/UsergeTeam/Userge/?ref=repository-badge)
[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/UsergeTeam/Userge)

> **Thunder** is a Powerful , _Powerful_ Telegram UserBot written in _Python_ using [Pyrogram](https://github.com/pyrogram/pyrogram).

## Inspiration 😇

> This project is inspired by the following projects :)

* [tg_userbot](https://github.com/watzon/tg_userbot) ( heavily ) 🤗
* [PyroGramUserBot](https://github.com/SpEcHiDe/PyroGramUserBot)
* [Telegram-Paperplane](https://github.com/RaphielGang/Telegram-Paperplane)
* [UniBorg](https://github.com/SpEcHiDe/UniBorg)

> Special Thanks to all of you !!!.

## Features 😍

* Powerful and Very Useful **built-in** Plugins
  * gdrive [ upload / download / etc ] ( Team Drives Supported! ) 🤥
  * zip / tar / unzip / untar / unrar
  * telegram upload / download
  * pmpermit / afk
  * notes / filters
  * split / combine
  * gadmin
  * plugin manager
  * ...and more
* Channel & Group log support
* Database support
* Build-in help support
* Easy to Setup & Use
* Easy to add / port Plugins
* Easy to write modules with the modified client



## Requirements 🥴

* Python 3.8 or Higher 👻
* Telegram [API Keys](https://my.telegram.org/apps)
* Google Drive [API Keys](https://console.developers.google.com/)
* MongoDB [Database URL](https://cloud.mongodb.com/)

## THUNDER MODES 🕹

* **USER** mode `(using user account)`
* **BOT** mode `(using bot account)`
* **DUAL** mode `(using both user and bot account)`

  > further **read** [config.env.sample](https://github.com/UsergeTeam/Userge/blob/alpha/config.env.sample)

## How To Deploy 👷

* With Heroku:
  > **NOTE** : your can fill other vars as your need and they are optional. (settings -> reveal config vars)
  * First click [**this**](https://heroku.com/deploy?template=https://github.com/Madhavreddy672/teamthundersuserbot/tree/master)
  * Fill `API_ID`, `API_HASH`, `DATABASE_URL` and `LOG_CHANNEL_ID` (**required**)
  * Choose your [**MODE**](https://github.com/UsergeTeam/Userge#userge-modes-)
  * Then fill other **non-required** vars as relevent to your **MODE**
  * Finally **hit deploy** button

* With Docker 🐳 
    - [**See Detailed Guide**](resources/radmeDocker.md)

* With Git, Python and pip 🔧
  ```bash
  # clone the repo
  git clone https://github.com/Madhavreddy672/teamthundersuserbot.git
  cd Userge

  # create virtualenv
  virtualenv -p /usr/bin/python3 venv
  . ./venv/bin/activate

  # install requirements
  pip install -r requirements.txt

  # Create config.env as given config.env.sample and fill that
  cp config.env.sample config.env

  # get string session and add it to config.env
  bash genStr

  # finally run the Userge ;)
  bash run
  ```

* **[More Detailed Guide](https://docs.google.com/document/d/15uoiOn2NkN518MMkx9h5UaMEWMp8aNZqJocXvS0uI6E)** 📝

### Video Tutorial 🎥

  [![Tutorial](resources/tutorial.jpg)](https://youtu.be/M4T_BJvFqkc "Tutorial")

### Support & Discussions 👥

> Head over to the [Discussion Group](https://t.me/madhav_reddy) and [Update Channel](https://t.me/theUserge)

### Copyright & License 👮

* Copyright (C) 2020 by [ThunderTeam](https://github.com/MadhavReddy672) ❤️️
* Licensed under the terms of the [GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007](https://github.com/UsergeTeam/Userge/blob/master/LICENSE)
