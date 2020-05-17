# A look at Airbnb listings in Montréal

## Table of contents
* Introduction and Motivation
* Repo content
* Setup
* Findings

## Introduction & Motivation
The purpose of this is to try and answer 3 questions related to Airbnb listing in Montréal given a listings dataset downloaded from Airbnb public datasets.
The questions are:
* What is the percentage of listings per neighbourhood in Montréal?
* What is the distribution of the different listing types?
* How much does it cost to rent an Entire home or apartment vs a private room?

## What is included in the repo:

- listsings.gz.csv: a zip format of the dataset. This could be download as well by running the approperiate cell in the jupyter notebook.
- airbnb_mtl_prices.ipynb: a jupyter note book where the analysis is done.
- requirements file: The required libraries to run the jupyter notebook.

## Setup:

**Note**: 

The code is part of a jupyter notebook and you need python 3.6 + to run it as the code uses f strings which was only supported on 3.6 and above.

To start after cloning the repo:

1. Create a virtual Environment(venv):
`$python3 -m venv /path/to/new/virtual/environment`

2. Go to the location of the venv, and run the following to activate it:
`$source bin/activate`

3. Install requirements:
`$pip install -r requirements.txt`

you can either use the dataset that is already in the repo, which is put in the correct path. Else you can run the cell in the jupyter notebook that downloads the dataset from source.

## Findings:
A blog link on the findings can be find here:
https://medium.com/@fbarazi/a-look-at-airbnb-listings-in-montreal-3c0c5512e380

* More than half of the listings in Montréal can be found in 2 neigbhourhoods; Ville Marie and Plateau area.  Looking further on the top 4 neighbourhoods that account for more than 70% of the listings, they are all central in well connected areas by public transport.
* 70% of the listings are entire homes/apt and around 28% are private rooms.
* The median price for an Entire home/apt is around 100$ and around 45$ for a private room.

## Aknowledgment:
The data used in this analysis is the detailed listings data for  Montréal, collected on 20th of April, 2020 is provided at:
http://insideairbnb.com/get-the-data.html
Direct link to the listings file:
http://data.insideairbnb.com/canada/qc/montreal/2020-04-20/data/listings.csv.gz


