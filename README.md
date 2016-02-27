# git weather
A nifty weather command for git lovers

Before you get started, you must have a [Weather Underground API Key, or sign up to get one](https://www.wunderground.com/weather/api/)

## Setup
Add the git-weather script to your path like so

```sh
export PATH=$PATH:<path to git-weather folder>
```


Alias git-weather to enable autocomplete

```sh
git config --global alias.weather weather
```


Add your API key and location to settings.json

```json
{
    "API_KEY": "api key goes here",
    "Location": "San Francisco, CA"
}
```

## How to use
Execute the following in your terminal


```sh
git weather
```
