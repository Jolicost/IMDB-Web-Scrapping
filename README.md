# IMDB Web Scrapping
This repository contains the code that deploys and automatic robot that scraps the IMDB website in order to obtain certain data from a given set of movies. The project scope is educational and must not be used under any circumstance for commercial purposes. 

This project was developed by:

* Ana Cortés Besolí: developer.
* Joan Oliva Costas: main developer.

## Usage
In order to execute the robot, you will need Python (>3), the libraries specified in the requierements.txt file and the Selenium web driver for your browser.

The [Usage](usage.md) file contains more information about how to use the application.

## File description
The files of the project are the following:

* main.py: main startup point of the application.
* movies.py: movies parser module.
* movie.py: movie parser module.
* reviews.py: review parser module.
* utils.py: utilities.
* copyConfig.py: deployment file.
* purgeOutput.py: deployment file for erasing scrapped data. 
* README.md: this exact file.
* usage.md: requierements and basic usage of the application.
* requeriments.txt: pip libraries.


## Greetings and license
The data that could be extracted using this tool and only be used for academical purposes. Always cite IMDB as the original author of the data. You are not allowed to make any commercial use of this application or the data extracted using it.

IMDB is the original owner of the movie and review data. 

We deeply thank IMDB for its courtesy to let us use their data for educational purposes.

The license for the data extracted using this application operates under CC BY-NC-SA 4.0. 

## Data DOI
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4155443.svg)](https://doi.org/10.5281/zenodo.4155443)



