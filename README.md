# NYC CRASHES - DATA CLEANING PROJECT

![NYC Traffic Picture (Image)](https://assets.bwbx.io/images/users/iqjWHBFdfxIU/iyCf091K_jqk/v0/-1x-1.jpg)

## The Mission

Bill de Blasio, mayor of New York City, is in a bit of a pickle. Indeed, his police department, the NYPD, collected information about all the traffic accidents that happened in New York City. However, they are too busy eating doughnuts to correctly encode each traffic incident, and so it happens that the dataset that we got here is quite dirty, has a lot of missing values and can't be used by a machine learning model as is. Can you help Mr. de Blasio and shine a new light on his police department ?

What he wants exactly is to predict which streets are the most dangerous while visiting the city that never sleeps.

I am well-equipped to handle this!

## Data Cleaning

>1. dtype changing
>
>2. duplicate check
>
>3. columns drop (redundancy)
>
>4. cells consolidating (to lowercase)
>
>5. columns rename
>
>6. collision_id set as Index
>
>7. narrow cars_types and contributing_factors (replace)
>
>8. One Hot Encode (car_types & contributing_factors)
>
>9. Drop NaN values rows
>
>10. Write to csv file
>

## Final Dataset

`Int64Index: 91965 entries, 225766 to 4353706`<br/>
`Data columns (total 74 columns):`<br/>
`dtypes: float64(2), int64(10), uint8(62)`<br/>
`memory usage: 14.6 MB`<br/>

## Files included

>`Readme.md`
>
>`crash_cleaning.ipynb`<br/>
>
>`nyc_crash_dataset.csv`
>
