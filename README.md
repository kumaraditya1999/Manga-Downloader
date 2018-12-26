# Manga Downloader

A python 3 script to download manga 

## Getting Started

Currently only script for downloading manga from kissmanga is avalable.**Install requests,img2pdf,selenium,PIL and io module**. Clone this repo and then run the command python/python3 kissmanga.py 

### Prerequisites

Install the modules requests,img2pdf,selenium,PIL and io.(using pip)
Install the gekodriver for selenium firefox driver (https://dzone.com/articles/python-getting-started)

### How to run the program

Run the command python kissmanga.py 
Give the proper manga name to be searched.
It will generate a list of manga or directly got to the manga chapter list.
Select the proper manga serial number.
For downloading the chapters:
+ give all to download all the chapters
+ give one index to download only that chapter
+ give two index (starting and ending) to download multiple series of chapters
It will create a dowloads folder.In that folder you will have your manga_named folder and in that folder you will have your pdf for the chapters you dowloaded.

### PS

The project is still in development stage so it may contain lots of bugs.Also it uses selenium so downloading may be slow and may generate timeout exception. Please feel free to create issues.
