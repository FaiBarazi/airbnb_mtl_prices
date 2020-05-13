# airbnb_mtl_prices
Predicting Airbnb prices in the Greater Montreal Area

This is a quick exploratory exercise of Airbnb listings in Montreal looking at the listings in relation to neighbourhoods and listing type.

The code is part of a jupyter notebook and you need python 3.6 + to run it as the code uses f strings which was only supported on 3.6 and above.

To start after cloning the repo:

1. Create a virtual Environment(venv):
`$python3 -m venv /path/to/new/virtual/environment`

2. Go to the location of the venv, and run the following to activate it:
`$source bin/activate`

3. Install requirements:
`$pip install -r requirements.txt`

you can either use the dataset that is already in the repo, which is put in the correct path. Else you can run the cell in the jupyter notebook that downloads the dataset from source.

A blog link on the findings can be find here:
https://medium.com/@fbarazi/a-look-at-airbnb-listings-in-montreal-3c0c5512e380

**Note**:
I decided not to create a predictive model for this because:
* Most of the entries are concentrated in 2 major neigbhourhoods, the data is already skewed location wise. 
* Most of the entries (70%) are for Entire homes/houses.
* After cleaning the data and removing exotic entries (houses for more than 12K per night with half of that as deposite that has no bedrooms) I am left with around 13K entries which are not necessarily enough for a good predictive model.
