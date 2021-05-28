<!-- PROJECT LOGO -->
<br />
<p align="center">
 <a href="https://github.com/sassansh/Heroku-PHP-MySQL">
    <img src="/images/logo.png" alt="Logo" width="80" height="80">
  </a>
  <h2 align="center">PHP & MySQL on Heroku ✨</h2>

  <p align="center">
    Deploying a hello world PHP app with a MySQL database on Heroku. View live demo: <a href="https://php-getting-started-sassansh.herokuapp.com/">php-getting-started-sassansh.herokuapp.com</a>
    <br />
    <br />
    <a href="https://sassanshokoohi.ca">About Me</a>
    ·
    <a href="https://github.com/sassansh/Heroku-PHP-MySQL/issues">Report Bug</a>
    ·
    <a href="https://github.com/sassansh/Heroku-PHP-MySQL/issues">Request Feature</a>
  </p>
</p>

![GitHub contributors](https://img.shields.io/github/contributors/sassansh/Heroku-PHP-MySQL?color=ffcc66&style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/sassansh/Heroku-PHP-MySQL?color=ffcc66&style=for-the-badge)
[![GitHub forks](https://img.shields.io/github/forks/sassansh/Heroku-PHP-MySQL?style=for-the-badge)](https://github.com/sassansh/Heroku-PHP-MySQL/network)
[![GitHub issues](https://img.shields.io/github/issues/sassansh/Heroku-PHP-MySQL?color=ffcc66&style=for-the-badge)](https://github.com/sassansh/Heroku-PHP-MySQL/issues)
[![GitHub license](https://img.shields.io/github/license/sassansh/Heroku-PHP-MySQL?style=for-the-badge)](https://github.com/sassansh/Heroku-PHP-MySQL/blob/master/LICENSE)
[![LinkedIn][linkedin-shield]][linkedin-url]

[![Site preview](/images/screenshot.png)](https://php-getting-started-sassansh.herokuapp.com/db/)

## Table of Contents

- [Technology Stack 🛠️](#technology-stack-)
- [Prerequisites 🍪](#prerequisites-)
- [Setup And Deployment 🔧](#setup-and-deployment-)
- [Contact 📧](#contact-)

## Technology Stack 🛠️

[PHP](https://www.php.net/)
| [MySQL](https://www.mysql.com/)

## Prerequisites 🍪

Install the [Heroku Toolbelt](https://toolbelt.heroku.com/).

## Setup And Deployment 🔧

1. Followed this guide: [Getting Started with PHP on Heroku](https://devcenter.heroku.com/articles/getting-started-with-php)

2. Run the following bash commands:

```sh
$ git clone git@github.com:heroku/php-getting-started.git # or clone your own fork
$ cd php-getting-started
$ heroku create
$ git push heroku main
$ heroku open
```

3. The deployment is now running at:

```text
https://php-getting-started-sassansh.herokuapp.com/
```

4. The `/hello` route returns the word Hello repeated by the value of the TIMES environment variable:
```text
https://php-getting-started-sassansh.herokuapp.com/hello
```

5. The `/cowsay` route will render a beautiful cow:
```text
https://php-getting-started-sassansh.herokuapp.com/cowsay
```

6. The `/db` route will return all rows in the test_table table on the MySQL database:
```text
https://php-getting-started-sassansh.herokuapp.com/db
```

## Contact 📧

Sassan Shokoohi - sassansh@student.ubc.ca

Project Link: [https://github.com/sassansh/Heroku-PHP-MySQL](https://github.com/sassansh/Heroku-PHP-MySQL)

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/sassanshokoohi/
