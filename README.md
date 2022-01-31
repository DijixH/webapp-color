# Web App Color image for aarch64

Web App Color is a website with a colored background. 

## Usage

With this command, you can run the web page with a random color :

`docker run --name webappcolor -d -p 8080:8080 thtom/webappcolor`

### Change background color

You can change background color with an environment variable :

`APP_COLOR=[COLOR]`

You have choice between : "red", "green", "blue", "blue2", "darkblue", "pink"

#### Example

For red background :

`docker run --name webappcolor -d -p 8080:8080 -e APP_COLOR=red thtom/webappcolor`


[Docker Hub Page](https://hub.docker.com/r/thtom/webappcolor)
