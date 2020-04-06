# browserless-chrome

This is a dead simple wrapper of [browserless/chrome](https://github.com/browserless/chrome) for deploying it on Heroku.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/ninoseki/browserless-chrome)

## Usage (on local)

```bash
docker build -t browserless-chrome .
docker run -p 3000:3000 browserless-chrome
```

## Configuration

- https://docs.browserless.io/docs/docker.html
