<p align="center">
    <img src="https://github.com/JJaraM/blog-microservice-ui/blob/master/src/main/resources/public/logo-210x.png" height="210">
</p>

<p align="center">
    <h2 align="center">Spring Cloud Configuration Server</h2>
    <p align="center">A spring configuration server implementation based on git implementation</p>
</p>

<p align="center">
    <a href="https://codecov.io/gh/JJaraM/blog-microservice-post">
      <img src="https://codecov.io/gh/JJaraM/blog-microservice-post/branch/master/graph/badge.svg" />
    </a>
    <a href="https://travis-ci.org/github/JJaraM/blog-microservice-post">
      <img src="https://travis-ci.org/JJaraM/blog-microservice-post.svg?branch=master" />
    </a>
    <a href="https://codeclimate.com/github/JJaraM/blog-microservice-post/maintainability">
       <img src="https://api.codeclimate.com/v1/badges/616202951ec1ab5a65bb/maintainability" />
    </a>
    <a href="https://codeclimate.com/github/JJaraM/blog-microservice-post/test_coverage">
        <img src="https://api.codeclimate.com/v1/badges/616202951ec1ab5a65bb/test_coverage" />
    </a>
     <a href="http://hits.dwyl.com/JJaraM/blog-microservice-post">
        <img src="http://hits.dwyl.com/JJaraM/blog-microservice-post.svg" />
    </a>
     <a href="https://pr-microservice-config-server.herokuapp.com/login">
        <img src="https://heroku-badge.herokuapp.com/?app=blog-microservice-post&style=flat" />
    </a>
</p>

<p align="center">
    <a href="https://pr-microservice-config-server.herokuapp.com/login">View Demo</a>
    ·
    <a href="https://github.com/JJaraM/blog-microservice-post/issues/new/choose">Report Bug</a>
    ·
    <a href="https://github.com/JJaraM/blog-microservice-post/issues/new/choose">Request Feature</a>
</p>

<p align="center">
    <a href="/docs/README.md">English</a>
    ·
    <a href="/docs/README_ES.md">Español</a>
</p>

# Getting Started
This is an implementation that shows how works spring configuration server on a spring cloud environment
for this implementation I used git client for a private repository to fetch the 
properties that all the cloud applications are going to use.

The plan of this configuration server is to make possible to load the application configuration
on runtime without restart them, so in that way we can make sure that the application
will be 24/7 live in a real world scenario.

If you want to take this application as template for some of your projects you will need to 
add the following parameters in the `bootstrap.yml` or save in the server, which is better
to hide the credentials for your configuration server.

```
spring.cloud.config.server.git.uri=
spring.cloud.config.server.git.username=
spring.cloud.config.server.git.password=
```
