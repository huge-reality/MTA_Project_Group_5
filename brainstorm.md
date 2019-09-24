# Brainstorm

## Questions: What do we want to learn?

>> We want to learn which stations have the highest amount of traffic, as well as when they experience high traffic.
Additionally, it would be a bonus to hypothesize where larger numbers of women in tech are getting on and off the
subway, and when.

>> The sample emails shared with us give us some hints: what we want to create at first is a list of stations that
are used for commuting, rather than by tourists. We can find stations with large traffic numbers that have significant
drops in traffic during weekends.

>> We will also want to look at hourly data so that we can say when the street teams should go out.

>> We might want to look at the number of devices per station — the more turnstiles their are, the lower proportion
of riders the street teams will encounter (most likely).

>> Overlaying with other data. They should be "aligned" with the values of the organization (feminist/tech-friendly/
liberal, etc.) and likely to contribute (wealthy). 

## Data: What is wrong with the data?

>> The Entry and Exit data is stored as a cumulative count, rather than as change. The problem with simply creating
a new column with the differences is that when you switch to a new turnstile, the count is different. 
