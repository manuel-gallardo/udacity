# Explore US Bikeshare Data

The following project consist to build a python program to analise statistics of for three major cities in the United States—Chicago, New York City, and Washington.


## Dataset

The provided datasets was for three major US cities contains the same six (6) columns:

    Start Time (e.g., 23-06-2017  15:09:32)
    End Time (e.g., 23-06-2017  15:14:53)
    Trip Duration (in seconds - e.g., 321)
    Start Station (e.g., Wood St & Hubbard St)
    End Station (e.g., Damen Ave & Chicago Ave)
    User Type (Subscriber or Customer)

Meanwhile, Chicago and New York City datasets also have the following two columns:

    Gender (Male or Male)
    Birth Year (e.g., 1975)

Time

## Project structure

This project was structured on the following functions:

        city, month, day = get_filters()
        df = load_data(city, month, day)
        time_stats(df)
        station_stats(df)
        trip_duration_stats(df)
        user_stats(df)

get_filters()

load_data(city, month, day)

time_stats(df)

station_stats(df)

trip_duration_stats(df)

user_stats(df)


