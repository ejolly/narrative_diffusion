# Narratives Diffusion

## Setup Python environment

*[Requires Anaconda installation](https://www.anaconda.com/products/distribution)*

`conda env create --name narratives --file environment.yml`

## Setup API keys

1. [Spotify API](https://developer.spotify.com/dashboard/applications)
2. [Genius API](https://genius.com/api-clients/new)
3. Add keys to `.env-example` and rename the file to `.env`

## Export environment when adding new packages

`conda env export > environment.yml`