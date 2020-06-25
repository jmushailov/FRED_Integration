import pandas as pd
import get_fred

list_for_fred = ['unrate','PCU3255103255107', 'houst', 'dspic96']
fred_variables = get_fred.get_fred(list_for_fred,observation_start = '2016-01-01', observation_end = '2019-12-31')

# merge a dataset with the fred DF
dat = pd.merge(dat, fred_variables, on ='date' )
