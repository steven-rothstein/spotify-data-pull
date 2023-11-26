# Spotify API Proof of Concept

This repository is meant to showcase some of the capabilities of the Spotify API and how its data could be ETL'd and analyzed.

The following example visualizations were generated using anonymized data from this application inputted into [Flourish](https://flourish.studio).

- [Bar Chart Race - Top Artists by Track Count: Growth Over Time](https://public.flourish.studio/visualisation/12648708/)

- [Racing Line Chart - Artist Rankings by Liked Track Count](https://public.flourish.studio/visualisation/12584673/)

- [Bubble Chart - Artists by Track Count](https://public.flourish.studio/visualisation/12649979/)

To fully use this repository, you will need the following:

- Python and all of the libraries at the top of `/spotify_data_pull.ipynb` installed (i.e. `pandas`, `matplotlib.pyplot`, etc.).

- Jupyter Notebook

- Tableau Desktop

- *Optional:* pandoc

## Instructions to Get Started

After installing all required tools, rename `/config/config_template.yml` to `/config/config.yml`.

Next, register / follow the instructions within the [Spotify Developer portal](https://developer.spotify.com/documentation/web-api) to retrieve your client id and client secret. Input these 2 fields' respective values into `/config/config.yml`. Also enter the username (email) and password of the Spotify user to run the Juypter Notebook against. This user should be allowed to use your application within the Spotify Developer portal per the documentation linked above.

## Repository File Structure

- **/.gitignore**

  A very simple file to help with file management.

- **/README.md**

  This file.

- **/spotify_data_pull.ipynb**

  The Jupyter Notebook where all of the fun happens.

- **/config**

  Contains Spotify app and user credentials for the Juypter Notebook.

- **/data_out**

  The Jupyter Notebook places output files here.

- **/example.zip**

  Example (anonymized) files including a Tableau dashboard.

- **/style**

  Contains CSS files for pandoc conversion from ipynb to HTML.