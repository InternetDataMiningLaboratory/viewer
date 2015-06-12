# Supported tags and respective `Dockerfile` links

- None

# What is viewer?

Viewer is the image of the front side server of a information service project called Company Service. The image contains a web server building in Tornado web framework and adds the code of the website. 

# How to use this image?

## Create and run viewer

```bash
    docker run -d -e "DATABASE_USER=xxxx" -e "DATABASE_PASSWD=xxxx" -e "COOKIE_SECRET=xxx" -P companyservice/viewer
```

> NOTICE     
> The environment variable **DATABASE_USER**, **DATABASE_PASSWD** and **COOKIE_SECRET** is required

# Supported Docker versions

This image is officially supported on Docker version 1.6.0.

Support for older versions (down to 1.0) is provided on a best-effort basis.
