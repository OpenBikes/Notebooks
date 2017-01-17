# Notebooks

Ordered by creation.

| Name                                          | Description                                                                   | Author(s)   |
|-----------------------------------------------|-------------------------------------------------------------------------------|-------------|
| [Graph connecting](graph_connecting.ipynb)    | Determining how to connect bike stations on a graph simply by using distance. | Max Halford |
| [Challenge 2016 hourly average](challenge_2016_hourly_average.ipynb)    | Forecasting the number of bikes at a station by looking at the average number of bikes per hour and day. | Max Halford |
| [Challenge 2016 random forest](challenge_2016_random_forest.ipynb) | Forecasting the number of bikes at a station with a Random Forest. | Max Halford |
| [Challenge 2016 time series](challenge_2016_time_series.ipynb) | Forecasting the number of bikes at a station with an ARIMA process. | Max Halford |
| [Challenge 2016 poisson process](challenge_2016_poisson_process.ipynb) | Forecasting the number of bikes at a station with a nonhomogeneous poisson point process. | Max Halford |

The notebooks prepended with `challenge_2016` are the ones Max Halford made during the OpenBikes Challenge of 2016; the notebooks suppose there exists a folder called `challenge_data/`, containing data from the [challenge website](http://challenge.openbikes.co/).

## Installation

```sh
$ pip install -r requirements.txt
```

## Ideas

- http://toddwschneider.com/posts/a-tale-of-twenty-two-million-citi-bikes-analyzing-the-nyc-bike-share-system/
- http://blog.nycdatascience.com/student-works/detecting-anomolous-events-in-washington-dc-bike-sharing-dataset/
- https://jakevdp.github.io/blog/2014/06/10/is-seattle-really-seeing-an-uptick-in-cycling/
- http://blog.revolutionanalytics.com/2016/01/new-yorkers-municipal-bikes-and-the-weather.html
- Consider nearby metros.
