# Explore US Bikeshare Data

This project consist to build a python program to analise statistics of for three major cities in the United States—Chicago, New York City, and Washington.
Therefore, this could lead to futher analysis like to obtain results of best usage, avoiding long riding from a single user, type of users, most popular station, etc.


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


## Project structure

This project was structured on the following functions:

        city, month, day = get_filters()
        df = load_data(city, month, day)
        display_df(df)
        time_stats(df)
        station_stats(df)
        trip_duration_stats(df)
        user_stats(df)
    
    get_filters()  
        This function will asks user to specify a city, month, and day to analyze. It was used dictionaries of cities and month to avoid 
        some missconfussion when user type their preference. The output to next functions are city as string, month as string, day as string. 

    load_data(city, month, day)
        Acording with preference of city, month and day, it will filter the dataframe based on the user selection and it will return as dataframe.

    display_df(df)
        Due to the project's requirement, this function will ask to user to display the first 5 raw data available of the selected input of the 
        previous function.

    time_stats(df)
        This function will display statistics on the most frequent times of travel. 

    station_stats(df)
        This function will displays statistics on the most popular stations and trip

    trip_duration_stats(df)
        This function will displays statistics on the total and average trip duration

    user_stats(df)
        This function will displays categorical statistics count of mens/women and birth year. 

