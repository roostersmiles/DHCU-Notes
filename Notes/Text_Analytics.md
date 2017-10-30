##Initial Notes from Review of Readings

- TA as a tool
- over quantification
- bias of the analyst
- ensuring it alights with research objectives
- difficult to use for complex ideas/thoughts
- cost-effective
- the structure and use of the tools drives the validity and replicability of the analysis. 
- importance of identifying the methodology used and filters/features of the tool in order to allow others to replicate.
- Need for a benefits/drawbacks of different tools and identification of what cases they are best used for.

##In class notes - Oct 30th
- text - more complicated than words
- what can be included, our understanding different, unconcious knowledge

###defining text analysis
- process of identifying patterns and trends in text
- Can it be done manually? - ENG Lit, 
- something about defining the data set, what is the source a sample universe
- GROUP: Text analysis is a process that allows for information/significance of meaning to be apprehended from data as a means to track, identify & compare patterns and trends to work towards a conclusion.
- discussion of what is data and the subjective/objective nature, 'well the data said this...'

###Close Reading vs. Distant Reading
- another difference between large scale and small scale? Volume? 
- subjective vs. objective distinction - perception
- anxiety of change - fomo, disciplined to think in certain ways, comfort level across disciplines, push against other ways of doing things
- adaption - scrambling, broad definitions, 

###Acivities
- counts - what is the use of this? random words?
- functional vs. contextual words - frequency

###Visualization
- Word cloud - larger word more frequently, lacks context
- Sentiment - database is important, source of analysis tool, semantic vector of a word, ratemyprof - context word about gender changes
- ran 5-6, overall neutral, 
-AntConc - tutorial on programming historian about how to use (words before and after, frequency)
- Limitations across them, shiney hammer problem - frequency of use, how they graph together
- corpus.byu.edu
- voyant - McGill/Alberta co collaboration
- there is a manual with background info for more information
- doc titles with numbering or dares will allow for a timeseries graph
- 
##Lecture
- Mining the dispatch, Newspaper from 1860-165 - civil war, character rec to turn images to text, corrected it.
- computer science indexing - topic modelling, put text in, identifies topics and can trend over time
- Mallet - command line, to feed data into it, started using it for everything
- Scott Winegard and Ian Milligan - lead to book
- once one person writes it down, becomes easier, fashion in tools, 'out of fashion' applying too far, few cases of meaningful ways
- be leary of letting tech drive analysis, find tool that helps solve core question,
-cool, to see patterns over a large body, a distribution over distributions, machine looking at each word in relationship to others within doc and across documents/corpus
- pull them out and assemble them, - tokens
- what are the buckets of words? concepts
- choose number of buckets, only a problem if you beleive there is an answer, proportions make mathematic sense
- need to say # an opportunity, what does it look like if we limit #, 
- collidescope, reading of the material, helped 
- Jstor articles 1935-2010 - Aaron Swartz, activist, invented RSS format, political arrest, The internets own boy
- Jstor impliment a thing call data for research - could dowload 20K in a particular format - article as a bag of words... - takes out of syntax context
- cluster of content words - numbers scaled to 100, inflection points, spikes with generational turnover
- patterns of computational thinking ahead of infrastructure available - can see with topic analysis and use of words
- supervised vs. unsupervised - topic modelling = unsupervised, not sure what partially supervised would be. 

##DHbox R
- gist.github.com/shawngraham - run to install packages (Not working for me atm, Shawn says slow wait)
- joundell.net - can pull annotations for hypothesis using API once logged in.
- Can export as a .csv file
- Using annotations from hypothesis - removed URL and meta data, kept date and text only.
- interpretive decisions made in using and working with data, make note of why and hope to acheive.
- in DH box need to load file into file manager- if on own PC can use from PC. 
- stop word list = words to skip, does so by comparing lists
- LDA - latent dirlichet allocation - formal name for algorithm being used, know which one is used
- know when it is done by triangle instead of stop sign in run window
- 
