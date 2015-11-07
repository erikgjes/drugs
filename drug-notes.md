##Drug notes October 30

###data issues
From the fda we have a list of 1249 NMEs

- 1276 total
	- 114 lack origination
- 278 discontinued
	- 93 lack orgination
	- 95 lack extinction
- 998 active
	- 21 lack origination
	- num with extinction dates
- Can we model origination and extinction of drugs conditioned on 3 kinds of data 
- Daniele figured out poisson versus b-d likelihoods normalized to allow comparisons
	- compare drug data
	- compare car data (use pyrate and thermal integration)

##We are going to run a pilot data set eliminating 
- 21 active without origination dates
- 95 discontinued that lack origination or extinction
- rates through time
- BD vs PD
- competition models
	- 