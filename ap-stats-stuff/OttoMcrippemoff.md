# Prob and Stats: Time for a Trial
Sam Young Wed Apr 19 19:50:34 EDT 2017

```
Otto McRippemoff claims that he provides the best auto repair service in the city. His
advertisements all claim that he has the best most reliable service over any other repair
shop in the city. Many customers have come forward to claim that Otto has lied to them
because their cars are breaking down after being repaired by his shop. These customers
are gathering together to take Otto to court. Judge Judy has agreed to oversee this trial.

Since you are a lawyer who knows you must use statistics to state your case and not just
opinion, you have collected some data from around the city as well as data from Otto’s
customers.

You know from previous very good data that 7% of cars repaired must be returned to a shop
to be fixed again.

You also randomly selected some of Otto’s repairs. Out of 200 repairs, 27 cars broke down
again within 90 days.

You would like to use this data to help determine that Otto is using false advertisement to
lure in customers by showing that not only is Otto not better than other repair shops, but
that he seems to be worse beyond a reasonable doubt.

Use your knowledge of statistics to create your case of evidence against Otto. Be prepared
to present this evidence in the Decker Court of Law. In other words, do the statistical
inference process necessary.

Write it out in detail so that you could explain it at the board. And make some notes to be
able to make statements to a judge so they can make a decision on the case. In other words,
describe what the p-value you found means as part of this evidence.
```

## Significance Test:

### Testing Conditions:
Normality?: `(.07*200)=14 and (.93*200)=186` Both of these results are greater than 10<br>
Testing for Randomness?: `Otto's cars that were tested were randomly selected.` <br>
Less than 10% of the Population?: `It is assumed that over the course of Otto's career, he has worked on over 2,000 cars.`

### Hypotheses:

H<sub>0</sub>: `P=0.7` <br>
H<sub>a</sub>: `P>0.7`

### Finding the Population Standard Deviation:
`sqrt((.07*.93)/200)=.0180`

### Finding sample probability:
`p̂=27/200`<br>`p̂=.135`

### Finding the Z-Score
`(.135-.07)/.018=3.61` <br>
Resulting P-value from Z-table: `.99985`
Chance of getting this statistic (P-Value): `1-.99985=.00015`

### Drawing
[Drawing](http://i.imgur.com/JbJF4be.png)

### Conclusion
With this small a P-value, `0.00015 < 0.05`, there is sufficient evidence to reject H<sub>0</sub>, that is, there is sufficient evidence that the true percantage of Otto's car repairs that ended up breaking down within 90 days is greater than 7%.

## What does the p-value mean in the context of this evidence and case?
In the context of this evidence and case, the P-value represents the probability of Otto's
car repairs that ended up breaking down within 90 days is greater than 13.5%.

## You are the lawyer representing the people against Otto.  Use your evidence to dispute Otto’s arguments.

### 1)  Otto:  “Your evidence is not valid.  It is biased against me.”
The evidence is valid, as the sampling method was random, the sample size was less than 10% of the population size, and enough values were accrued for the sample distribution to be approximately normal.

### 2)  Otto:  “How can you make your statements with so little evidence?”
There were enough trials performed to attain a normal distribution.

### 3)  Otto:  “It is possible to get results like yours even if I have just the same quality as the other repair shops in the city.  So, I claim that is what happened.”
This is highly unlikely, as 13.5% is beyond two standard deviations away from the population mean.

### 4)  Otto:  “Your test could have made an error.  The judge shouldn’t trust it.”
The chance of a Type I error is highly unlikely, at a minuscule .015% chance.

### 5)  Otto:  “You are a ***nincompoop*** and nothing you say should be trusted. “
In addition to this being an example of the `ad hominem` logical fallacy, Otto has also not provided any statistical evidence to back up his claim.

<br><br><br>

# New Problem: Significance Test of a single Proportion

```
1)  In the past, 15% of the raccoons seen ravaging trash cans during the daylight hours
had rabies.  It is believed that this percentage has increased.  So, 100 raccoons were
randomly captured during daylight hours once attacking a trash can.  Of these, it was
determined that 23 of them had rabies.  Perform a significance test to determine if the
percentage of rabies carrying raccoons attacking trash cans during the daylight hours has
increased.  Test at a level of significance of  = 0.05.
```

## Conditions
Normality?:`(.15*100)=15 and (.85*100)=85` Both of these are greater than 10 <br>
Random?: Raccoons were captured randomly <br>
Less Than 10% of the Population: I would certainly assume that there are more than 100 raccoons in the world

## Hypotheses
H<sub>0</sub>: `P=.15` <br>
H<sub>a</sub>: `P>.15`

## Finding Population Standard Deviation:
`sqrt((.15*.85)/100)=0.0357`

## Finding Sample Probability
`23/100=.23`

## Finding the Z-Score
`((.23-.15)/.0357)=2.24` <br>
P-value from Z-table: `.98745` <br>
Chance of getting this statistic (P-Value): `1-.98745=.01254`

## Drawing
[Drawing2](http://i.imgur.com/MmsmUao.png)

## Conclusion
With this small a P-value, .01254< .05, there is sufficient evidence to reject H<sub>0</sub>, that is, there is sufficient evidence that the true percentage of raccoons carrying rabies attacking trash cans during the daylight hours has increased.
