

<p align="center">
    An <a href="https://httpd.apache.org/docs/2.4/de/invoking.html">Apache httpd</a> and <a href="https://auth0.com/de">Auth0</a> plug & play solution.
</p>

### Prerequisits
You need to install <a href="https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04">docker</a> and <a href="">docker-compose</a> for the system to work. **Dont forget to set the docker command to work withou sudo.**

## Configuration
You need to create an account at Auth0 and generate an application. Ths lets you create credentials that allow your application to initiate the authentication.

```
Client id
Client Secret
``` 

In order to redirect to the right path you need to add the **correct callback URL** of the providing server.
This URL needs to match the allowed url at Auth0.

## Run
To start the httpd server, simply run
```sh
docker-compose up
```



