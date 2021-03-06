#  ...Implement rest of models
 * Read Hanes and Schalls, Science, 1996 for the (first) constant threhold accum observation.

## DEBUG or other issues



## ENHANCE:

* Set it up so that constructed function's names include their params or otherwise store the params in some kind of self documenting way.
* While Usher and McClelland (2001) showed that it can't scale, it need not here, and so it may be worth including a feed forward inhibition model too.
* Free 'x' version of lcba.
* Race, see LaBerge 1962 and Logan 2002
* Wang (2002) pooled inhibition (based on Bogsacz lineariztion in section 2.8 of the 'Physics of decision' paper.
* Yang and Shandlens (2007; the PR study) softmax/wieght variant
* Robust methods: Zackenhouse, Bogacz and Holmes (2010)
* Read Maddoxs COBRA paper ('Base-rate and payoff effects in multidimensional perceptual categorization'); implement?

# Other ENHANCEments:

* Option to save scores for each element of each trial
* Create way to visualize theoretical HRFs (both individual/trial-level and average) for each model.  This might be a surprise, or at least of use.  From this view some models will certainly conflict with the Wheeler 3 signal paradigm.

# Long term questions/issues

* How to sample trials with < 20 points; it is to massive to do exhaustively....  
 - Latin-hypercube style monte carlo?
 - Limit to 'interesting' subsets of Hamming D or rate, or some other trial
   measure.
* Parallelization?
