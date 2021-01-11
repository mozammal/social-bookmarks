# social-bookmarks

# About

Sample djnago social bookmarking application with mysql, redis, and docker-compose

# Running Locally
The only dependency for running this example is [Docker Compose][docker].

[docker]: https://docs.docker.com/compose/install/

You need to to configure an external SMTP serverand by editing the social_bookmarking.env file with your own values for EMAIL_HOST_USER, EMAIL_HOST_PASSWORD, etc. Once you are ready, you can start the application by executing the following command:

```sh
$ docker-compose up -d
```

If you want to tear-down the application, use the command written below:

```sh
$ docker-compose down
```

# The Django social bookamrking home page looks as follows:

![Screenshot](social-bookmarking.PNG)

![Screenshot](social-bookmarking1.PNG)




