# boston_airbnb
Diving into the data from Boston AirBnB listings

# Overview

As a resident of Greater Boston area, I decided to discover the city of Boston through data. Boston has many attractions concentrated in a small area, so I think it's worth a visit especially if the forecast doesn't look too bad! I will explore the data throughout the Jupyter notebook, but feel free to modify the variables and get more insights.

# Installation

folium: (use one of the two below)

pip install folium

conda install folium -c conda-forge

If you don't have the following libraries, Anaconda installation is strongly recommended:

pandas
matplotlib
seaborn


# Data

I got the data from Kaggle, which was updated 6 months ago. Admittedly, the data could have been more recent, but given the recent Covid-19 outbreak, more recent data might be skewed a bit from the 'normal' times.
https://www.kaggle.com/airbnb/boston


# Results

My biggest motivation going into the data was to see how prices are affected by different factors of an Airbnb listing. While none of the factors had a major correlation to the price, four factors had somewhat of an influence. Being located at more North and more East(which corresponds to Downtown Boston and Back Bay(affluent neighborhood)), having more guests included in the price and newness of the host all seem to somewhat increase the price. Transit options surprisingly seemed to have less of an effect, but the keyword 'subway' still somewhat increased the price as well.

Prices for the most popular top rated locations can also be seen on the map that I made with the help of folium library. This might actually be a useful feature to check out visiting a new city in the future as apps sometimes have the conflict of giving you the best match for your needs and making more profits!

Finally, I looked into different room types listed on Airbnb to see what kind of room type is the best to list on AirBnB in Boston. It seems that listing an entire apartment/home or a private room would be the best way to go to have a good occupancy rate. Either way, Boston listings seem to attract high prices.

I found one data point that was listed as a 'castle' for room type, but the property turned out to be in the North End, an old Italian neighborhood near Downtown with brick buildings. So it was just an apartment. What a bummer!
