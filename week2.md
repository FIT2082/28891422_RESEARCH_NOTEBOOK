# Simulation of air conditioners 

## Aim

Our aim is to simulate the behaviour of air conditioners via machine learning; we first have to look at a couple of things

1. Analyse the dataset and identify key variables
2. Analyse how outside tempreture impacts inside room tempreture
3. Identify a relationship if we can
4. Finally apply some machine learning techniques to see if we can simulate real AC behaviour
5. Find optimal AC set points that can help maintain tempreture


## Dataset

We have a large dataset of more than a dozen monash rooms and in it we have; **room tempreture**, **outside tempreture**, **AC set point**, 
**AC Status**. I looked at the data provided by Dr Arnaud and realised most of the data have half of the year missing however that is not a problem as we have data of 6 months each room and it is recorded every 15 minutes.

## Target for next week 

By next week I hope I can prepare a data_cleaning function which would be quite handy for us as there are many rooms we need to analyse. We must also produce some plots on outside and inside temp. Also work on project proposal draft.

We'd also like to cluster the data into four segments as suggested by Dr Christoph and Dr Arnaud

1. When AC is off and room temp is lower than outside temp
2. When AC is off and room temp is higher than outside temp
3. When AC is on and room temp is lower than outside temp
4. When AC is on and room temp is higher than outside tempgi