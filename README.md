# LuckyNumber7-Project1

Pulling Data

00_ This file was created in order to scrape the data via API.  We pulled in all necessary data and put it into a data frame, this was exported to excel in order to pass it to the next module

Data Frames / Scrubbing

01_ This jupyter notebook was created in order to scrub, and clean the data.  We brought the data into excel, and kicked out all things that did not make sense.  For example, we had "." that was pulled down instead of Null.  These issues, as well as null values were removed from the dataframe.  Finally, we made sure that the dataframe structure was consistent and that the columns were the right format in order to do some math on it.  Additionally, we created percentage changes in order to normalize the data

Analysis / Plotting

02_ This notebook was created in order to plot the data.  We created a function that we could pass necessary items to inorder to do a traditional x y linear regression.  Additionally, we wanted to go into the rabbit hole of non-linear regressions.  We did a 6th order regression to see how this looks.  Each regression was limited by year in order for us to see better trends.  We found that using all time (2010 to 2020) did not have great regressions so we then again had to limit across time.
