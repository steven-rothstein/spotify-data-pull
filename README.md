# Spotify API Proof of Concept

This repository is meant to showcase some of the capabilities of the Spotify API and how its data could be ETL'd and analyzed.

To fully use this repository, you will need the following:

- Python and all of the libraries at the top of `/spotify_data_pull.ipynb` installed (i.e. `pandas`, `matplotlib.pyplot`, etc.).

- Jupyter Notebook

- Tableau Desktop

- *Optional:* pandoc

## Instructions to Get Started

After installing all required tools, rename `/config/config_template.yml` to `/config/config.yml`.

Next, register / follow the instructions within the [Spotify Developer portal](https://developer.spotify.com/documentation/web-api) to retrieve your client id and client secret. Input these 2 fields' respective values into `/config/config.yml`. Also enter the username (email) and password of the Spotify user to run the Juypter Notebook against. This user should be allowed to use your application within the Spotify Developer portal per the documentation linked above.

## Repository File Structure

- /.gitignore

- /README.md

- spotify_data_pull.ipynb

- spotify_data_pull_custom.html

- spotify_data_pull_jupyter.html

- /config

- /data_out

- /example

- /style

- /viz

https://public.flourish.studio/visualisation/12584673/

https://public.flourish.studio/visualisation/12648708/

https://public.flourish.studio/visualisation/12649979/