
# Citibike mini project review by fb55                                                
                                                                                  
## IDEA:  
the idea is fine

## Null and alternative hypotheses

the null should alredy state what you measure; the mean number of rides? the ratio of week to weekend rides? Just saying "as likely or more" does not tell me what you are going to measure.

Idea: Subscribers are more likely than non-subscribers (users) to use Citibikes Monday through Friday.

Null Hypothesis: Non-subscribers (users) use Citibikes as much or more than subscribers Monday through Friday.


Alternative Hypothsesis: Non-subscribers use Citibike less than subscribers Monday through Friday.

you may want to measure the ratio of number of rides per week pver number of rides per weekend, and you may want to average over the 4 weeks of the month. You may want to look at the mean number of rides per week day (and its standard deviation) and per weekend day. Define what the target quantity is.



## data wrangling:

remove empty cells from your notebooks!

The data has to be moved into the PUIDATA directory; data should not be kept in the same directory as code, and for the class it has to be stored in PUIDATA so that we avoiding having multiple copies of redundant data as we grade 90 notebooks. so you should not get data from the puidata dir, which is your own so it only hosts data you downloaded in it, but put your data in that dir (so when we run it goes into our own $PUIDATA). If it is still not clear please do ask me what I mean.

why are you showing 79 rows?? that is a lot of rows!

you do not have to do this

```
df['usertype'] = df['usertype'].replace(['Subscriber','Customer'],[1,2])
```

because pandas deals well with categorical data even if it is not numerical. you probably would need to if you were using numpy for the analysis, btu with pandas it is superfluous

The data **may** support the question but you have not defined in the question what you want to measure so we cannot tell! Define your question in more detail, and finish prepping the data accordingly.


