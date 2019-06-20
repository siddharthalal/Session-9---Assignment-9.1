#### Create a DatetimeIndex that contains each business day of 2015 and use it to index a series of random numbers.

    1) Find the sum of the values in the DatetimeIndex for every Wednesday.

    2) Find the average for each calendar month.

    3) For each group of four consecutive calendar months in the DatetimeIndex, find the date on which the highest value occurred.

#### Read the dataset from the below link:

        https://raw.githubusercontent.com/guipsamora/pandas_exercises/master/06_Stats/US_Baby_Names/US_Baby_Names_right.csv

    1) Delete all un-named columns.

    2) Show gender wise distribution.

    3) Show the top 5 most preferred names.

    4) Find the median name occurence in the dataset.

    5) Show distribution of male and female born (count by states).
    
#### Clean up data in the given df:

    df = pd.DataFrame({'From_To': ['LoNDon_paris', 'MAdrid_miLAN', 'londON_StockhOlm',
                      'Budapest_PaRis', 'Brussels_londOn'],
                      'FlightNumber': [10045, np.nan, 10065, np.nan, 10085],
                      'RecentDelays': [[23, 47], [], [24, 43, 87], [13], [67, 32]],
                      'Airline': ['KLM(!)', '<Air France> (12)', '(British Airways. )',
                      '12. Air France', '"Swiss Air"']})

