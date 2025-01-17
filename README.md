<div id="top"></div>

[![Forks][forks-shield]][forks-url] [![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/moedaaboul/legogram">
    <img src="__admin__/resources/logo.png" alt="Logo">
  </a>

  <h3 align="center">Legogram</h3>

  <p align="center">
    The concept for this project was to provide lego creators with a social media platform similar to Instagram where they could share their love for everything to do with Lego.
    <br />
    <a href="https://github.com/moedaaboul/legogram"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://legogram.herokuapp.com/">View Demo</a>
    ·
    <a href="https://github.com/moedaaboul/legogram/issues">Report Bug</a>
    ·
    <a href="https://github.com/moedaaboul/legogram/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#user-story">User story</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#dependencies">npm dependencies</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

[![Login Screen Shot][login-screenshot]](https://legogram.herokuapp.com/login)
[![Feed Screen Shot][feed-screenshot]](https://legogram.herokuapp.com/)
[![Post Screen Shot][post-screenshot]](https://legogram.herokuapp.com/)

Through a combination of an exceptional concept with great technological
delivery through industry standard tools, the logogram app was created to meet
the demand and maintain an ethos that bares close relation to that of Lego’s.

Legogram is the perfect platform for users to come together and share their
passion for the Lego empire. A lot of functionality around providing features to
promote collaboration and communication have been purposely implemented to boost
the sense of community on the app.

<p align="right">(<a href="#top">back to top</a>)</p>

### User Story

- I can create (upload) new posts and delete (my) posts
- I can comment on other posts and delete my own comments.
- I can follow and unfollow other users.
- I can like and unlike other users.
- I can view posts by tag on click.
- I can add and edit tags to my posts
- I can browse lego creator profiles.
- Whem I browse Lego creator profiles, I can see activity stats and posted
  images.

### Built With

- [Javascript](https://www.javascript.com/)
- [Handlebars](https://handlebarsjs.com/)
- [Express](https://expressjs.com/)
- [Cloudinary](https://cloudinary.com/)
- [MySQL](https://www.mysql.com/)
- [Heroku](https://www.heroku.com/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

### Installation

0. Run deployed app at: https://legogram.herokuapp.com/
1. Clone the repo
   ```sh
   git clone git@github.com:moedaaboul/legogram.git
   ```
2. Install NPM packages
   ```sh
   npm i
   ```
3. Download and configure MySQL https://www.mysql.com/

### Prerequisites

Install all necessary dependencies by executing:

```sh
npm i
```

## Dependencies

```javascript
const express = require('express');
const routes = require('./controllers');
const sequelize = require('./config/connection');
const exphbs = require('express-handlebars');
const path = require('path');
const session = require('express-session');
const helpers = require('./utils/helpers');
const SequelizeStore = require('connect-session-sequelize')(session.Store);
```

<p align="right">(<a href="#top">back to top</a>)</p>

## Contributing

If you have a suggestion that would make this better, please fork the repo and
create a pull request. You can also simply open an issue with the tag
"enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->

## Hosting

| Project  | Legogram URL                      |
| -------- | --------------------------------- |
| Legogram | <https://legogram.herokuapp.com/> |

<p align="right">(<a href="#top">back to top</a>)</p>

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

> Muhammad Daaboul
> ![GitHub followers](https://img.shields.io/github/followers/moedaaboul?style=social)

> Heran Yang
> ![GitHub followers](https://img.shields.io/github/followers/heranYang93?style=social)

> Eoin Harkin
> ![GitHub followers](https://img.shields.io/github/followers/HarkyDev?style=social)

> Iler Watson
> ![GitHub followers](https://img.shields.io/github/followers/Iler22?style=social)

> Mbongeni Allan Ngwenya
> ![GitHub followers](https://img.shields.io/github/followers/Allan-Ngwenya?style=social)

<!-- > ![GitHub followers](https://img.shields.io/github/followers/heranYang93?style=social) -->

Project Link:
[github.com/moedaaboul/legogram](https://github.com/moedaaboul/legogram)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

- [Font Awesome](https://fontawesome.com)
- [Express](https://expressjs.com)
- [MySQL](https://www.mysql.com)
- [Sequelize](https://sequelize.org)
- [CodePen](https://codepen.io)
- [Bulma](https://bulma.io)
- [Cloudinary](https://cloudinary.com)
- [imgur](https://imgur.comm)
- [Heroku](https://id.heroku.com/login)

<p align="right">(<a href="#top">back to top</a>)</p>

[forks-shield]:
  https://img.shields.io/github/forks/heranYang93/Leg-it.svg?style=for-the-badge
[forks-url]: https://github.com/heranYang93/Leg-it/network/members
[issues-shield]:
  https://img.shields.io/github/issues/heranYang93/Leg-it.svg?style=for-the-badge
[issues-url]: https://github.com/heranYang93/Leg-it/issues
[license-shield]:
  https://img.shields.io/github/license/heranYang93/Leg-it.svg?style=for-the-badge
[license-url]: https://github.com/heranYang93/Leg-it/blob/master/LICENSE.txt
[linkedin-shield]:
  https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url-md]: https://www.linkedin.com/in/muhammad-daaboul-38470046/
[github-follow-shield-md]:
  https://img.shields.io/github/followers/heranYang93?style=social
[linkedin-url-hy]: https://linkedin.com/in/heranyang/
[github-follow-shield-hy]:
  https://img.shields.io/github/followers/moedaaboul?style=social
[linkedin-url-eh]: https://linkedin.com/in/eoin-harkin-229115216/
[linkedin-url-iw]: https://linkedin.com/in/iler-watson-643442158/
[linkedin-url-man]: https://linkedin.com/in/mbongeni-allan-ngwenya-220375170/
[login-screenshot]: /__admin__/resources/login.png
[feed-screenshot]: /__admin__/resources/feed.png
[post-screenshot]: /__admin__/resources/post.png
