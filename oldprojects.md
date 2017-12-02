<hr/>

## Proposed Projects (not all were done)

<hr/>

###Predicting passenger patterns on the T

Ginna Reeder, Dominick Tribo, *MBTA*

Using data from the MBTA’s fare collection system (which includes unique IDs for all cards and when and where the cards are used), students will develop predictive models of ridership patterns based on past travel. This will include both internal patterns (i.e. given the number of people boarding buses that feed into Forest Hills station, what can we expect for Orange Line ridership?) and the influence of external events (i.e. events at the Garden or Fenway, good vs. bad weather, etc.). Students will learn about the fundamentals of analyzing public transport data, regression modeling and factor analysis, and model calibration.

###Classifying everything on the sky

Edo Berger, *CfA*

Using the PS1 data we want to 
  a) Create time series catalogs (assuming this is easy and almost) for the MD fields 
  b) Create a training set for all kind of objects known to astronomers. For this to happen we need to use known objects for other surveys and transfer learning. Transfer learning is when a training set is not available as such but machine learning methods have to be used to do so
  c) Create a probabilistic classification model that classifies everything. Evaluate accuracy etc
  d) Given the classification, create a predictive model that can be used to evaluate follow ups. This can include time of next observation, what filters, how many epochs etc. THIS IS THE KEY and we need to have a good idea what would be useful to astronomers


###Social Media Epidemiology

Mauricio Santillana, *SEAS*

Preventing outbreaks of communicable diseases is one of the top priorities of public health officials from all over the world. Although traditional clinical methods to track the incidence of diseases are essential to prevent outbreaks, they frequently take weeks to spot critical epidemiological events. This is mainly due to the multiple clinical steps needed to confirm the appearance and incidence of diseases. Recently, the real time analysis of big data sets coming from Google, Facebook, Twitter, and other media coverage websites, has enabled researchers to propose new ways to perform internet-based public health surveillance. These new ideas have given rise to multiple digital disease surveillance systems capable of providing timely epidemiological information to public health decision makers (two to three weeks) ahead of traditional reports.

Challenges in the design and implementation of these digital disease tracking systems include finding, downloading, storing, analyzing, and visualizing enormous amounts of information continuously in time. 

###High-speed 3D volume registration for motion correction in magnetic resonance imaging

Dylan Tisdall, *SEAS*

High-speed 3D volume registration for motion correction in magnetic resonance imaging
Massachusetts General Hospital is a leader in the development of motion correction technology in magnetic resonance imaging (MRI). As part of our motion correction system for MRI, we acquire a series of low-resolution "navigator" volumes of a subject's head, and register the volumes (in approximately 20 ms) to estimate motion and dynamically update MRI scanning parameters in real time during scanning. We are seeking a Masters candidate to help implement and evaluate new algorithms for high-speed 3D volume registration, as we explore methods to improve the speed and accuracy of our motion correction system. Working with mentors experienced in MRI data and image registration, the candidate will implement candidate image-registration algorithms in C/C++, and subsequently profile, optimize, and evaluate the implementations using test data sets we have acquired from our MRI scanners.

###Assessing brain development for prematurely born babies.

Lilla Zollei, *SEAS*

Assessing brain development for prematurely born babies.We have currently completed a prototype of a structural MRI processing pipeline that annotates various brain areas in acquistions of infants.
The student would need to familiarize her-/himself with the tools, process a set of data from a prematurely born population and then modify and evaluate the accuracy of the pipeline. When completed, findings from this study would be compared to those from a population of full-terms. The student would be supervised one or two mentors experienced in MRI post-processing and image registration. Familiarity with C/C++, Matlab and basic scripting is a requirement.

###Detecting Topics and Understanding Citations

Alberto Accomazzi, *CfA*

Nearly every Physics, Astronomy, and Geophysics article refereed in the past 20 years is fully indexed and served by the ADS. 50,000 scientists and librarians use the ADS daily. The ADS’s bibliographic dataset currently consists of over ten million documents, and is growing at a rate of several thousand per month. There are multiple projects of interest, including:

* Detect topics from a paper using NLP techniques for entity recognition (could be an ontology, thesaurus, or just controlled dictionary).  
* Improve ADS’s reference resolving framework using state of the art techniques such as Conditional Random Fields (CRF).
* Extract the context in which a citation is provided in a paper and characterize its use.  This could involve running an existing text mining/tagging system, such as ScienceWise over the document collection, using an existing thesaurus or ontology, such as the ScienceWise crowd-sourced ontology or the Unified Astronomy Thesaurus to automatically create a subject matter annotated body of text.  The references in the text would then be coupled with the nearby (according to some proximity measure) subject matter tags to form an external view of the subject matter in the reference.  These views (one for each time an article is referred to in the text) can be combined, both within a document (if the referring article refers to the reference more than once) and within the set of all referring documents.  These can then be compared with each other, with the ctual descriptors of the referred to document itself, and with other similar documents to form a powerful new technique for search and discovery, an extension of the existing anchor-text methodology.

### Identifying Establishments With High Human-Trafficking Potential

Craig Heckman, *Polaris*

Polaris, an anti-human-trafficking organization, is interested in exploring how computational science can assist in identifying locations, businesses, and individuals participating in human trafficking operations.  Though human trafficking occurs in many industries, one industry that is especially interesting from a computational perspective is the erotic massage parlor industry.  Anecdotal evidence from the National Human Trafficking Resource Center hotline and from human trafficking survivors indicates that the industry is highly networked and that women in the industry are often coerced.

Since the erotic massage parlors operate as seemingly legitimate businesses, there is a significant amount of data and information about them on the web (public business records, "Yelp"-style customer review sites, customer forums, classifieds websites, massage license data, criminal records, news articles, social media, etc.) Through computational methods, Polaris hopes to: 
Better understand the erotic massage industry
Identify establishments with a high probability of involvement in trafficking activities
Establish probable links between establishments
Identify the most influential individuals / businesses in the industry


###Conceptual Physics from Machine Learning

Tim Kaxiras, Dogus Ekin, *SEAS*

Generally, we apply powerful machine learning and stochastic optimization methods to condensed matter physics. These computational methods can be used as a curve-fitting and optimization tool; this approach has been gaining popularity in many chemistry and physics subfields. We also utilize machine learning  directly to gain conceptual understanding not achieved with conventional approaches in physics. For example, we have used kernel SVMs and feed-forward neural networks to define the concept of a defect in disordered systems, which could not be done before. We are also working on using neural networks, with similar topology to recurrent networks in natural language processing, to find a good representation for atomic configurations in quantum mechanical calculations. Future direction is to focus on unsupervised learning to find meaningful representations of physical systems.

###Market Beta

Ross Levinsky, Matt Leffers, *HBK*

The broad problem is how to best estimate, given information available today, the relationship between the price of a stock and a market index in the future. 
 
This relationship is commonly referred to as the equity’s “market beta” and describes what percentage move in the stock we should expect given a one unit move up or down in the index. 
 
The simplest solution to the problem is to regress the prices or returns of a stock on the index return or price.  However, below are some considerations that merit further research to refine the estimate:
·         Is there an optimal backward-looking time scale if we are interested in predicting the relationship over the next week?

·         Are any corrections possible or optimal for stocks that are thinly-traded, and therefore may lag the more-liquid market index on a daily basis?  What about stocks listed and traded in the US, but with businesses abroad (e.g. ADRs)?

·         How should we handle newly-traded names (e.g. IPOs, spin-offs, etc)?

·         How should we handle a stock with recent large, idiosyncratic moves (e.g. those caused by significant company-specific news)?

·         Is there merit to the concept of “shrinkage”, i.e. that the beta relationship regresses to one over time?

·         How should we handle regime changes in the market (i.e. significant changes to the macro environment or other systematic factors which might bias our backward-looking estimate such as the market crash in 1987 or the global financial crisis of 2008)?

 

###Mortgage prepayment and Bitcoin

Vasily Strela, *Morgan Stanely*

Value of mortgage prepayment option (Cheng Su, *Morgan Stanely*):

* Q 1.            Estimate empirically for a period of time (say the past 10 years) how much homeowners paid for the option cost in mortgages and how much they saved when prepay. (For this one I believe homeowners are better off because rate has been dropping for the past 10 years)Q
* Q 2.            Compare the current option cost being charged vs the historical mean.
* Q 3.            Calculate how much more mortgage rate needs to drop for homeowners to break even given the option cost they are paying now.
 
Throughout this question we can look at 30Y fixed rate mortgages securitized by Freddie Mac since 2005 as sample data.
 
* Q 1. In US most mortgages come with an embedded option: borrowers can pay back their loans any time (called prepayment).
It is nice to have such an option because borrowers may not know exactly how long they will keep the property.
However, this option does not come free, and borrowers are paying a higher coupon rate for this option.
So the first question is to come up a method to measure overall how much extra premium borrowers paid to have the prepay option and apply this measure to the empirical data.
 
When borrowers pay back their mortgages before the maturity data, they might save some money if the mortgage rates they have are higher than the prevailing mortgage rate.
So the second question is how to measure how much money borrowers saved, and then apply this measure to empirical data.
Then we can compare whether borrowers paid more option premium or saved more from prepayment.
 
* Q 2. What is the option premium borrowers are paying today? How does it compare historically?
 
* Q 3. Given the option premium borrowers are paying now, in what interest rate (hence mortgage rate) scenarios borrowers recover the premium they pay for the option through prepayment.
 
Bitcoin (Alfred Yuan, *Morgan Stanely*):

Bitcoin (BTC), as you may hear about, is a digital currency. Unlike traditional currency whose credit is backed by government’s privilege of taxing, BTC is backed by a cryptology math algorithm. This nature makes BTC born in debate. Supporters claim this peer-to-peer (P2P) mode saves people from inflation hazard of traditional currencies; meanwhile, others argue once this algorithm is cracked by any party, BTC will become of 0 value.
However, after several years, BTC gradually became accepted by lots of mainstream stores / websites / companies as an alternative payment method. Born in digital era, BTC’s data are all available online easy to access. The project may include analysis in the following directions:
1.            Relationship between BTC and other global macro assets (including G10 currencies, Libor rates, oild prices and etc.)
2.            Possible arbitrage trading opportunities across different BTC exchanges
3.            The demand / supply (mining) of BTC market and how it affects the BTC price
4.            What’s the relationship between BTC and other digital currencies, such as LTC and etc.

###Long-Short equity trading strategies.

Apollo Wong, *Verition*

In this project students will be instructed to try to build an industrial strength Long-Short equity trading strategy using public domain data sources. Students will learn about the importance of factor selection, transaction cost, liquidity, proper usage of optimizer, and natural capacity constraints on strategies. They will learn about proper method of backtesting. If time permits, they could experiment with methods of improving the performance of various factors and solve real problems in real world trading. Students will also learn about the importance of computer science in financial industry.

###Deep Learning and the Brain Connectome.

Verena Kaynig-Fittkau, *SEAS*

**Deep learning methods for Connectomics**:

In the field of Connectomics, neuroanatomists are interested in the wiring diagram of the brain to learn more about its functional structure. To automatically build these diagrams from electron microscopy images using machine vision, we need to segment individual neurons and their synapses. Recent work has focused on deep learning methods for the detection of membranes in the images. While convolutional neural network so far yield the best results, they are inherently slow and cannot keep up with the data acquisition process. Goal of this master thesis is to explore other deep learning architectures to speed up the prediction without a significant loss in performance. Coding will be done in Python, using Theano and Pylearn2 as deep learning libraries. The data is already acquired and we have sufficient manual annotations for deep learning.

Keywords: Deep learning, Python, Theano, Connectomics.

**Higher level assembly of neuronal structures from error prone pre-segmentations based on biological models**:

Our lab has developed a computer vision pipeline for the segmentation of neurons from electron microscopy images. The ultimate goal is to identify the wiring diagram of these neurons to gain insight into the functional structure of the brain. Currently our automatic reconstructions need manual proofreading to correct for split and merge errors in the 3D geometry of the neurons. Goal of this master thesis is to build on top of the automatic reconstructions and correct split errors by looking at 3D segments and merging them into biological plausible neurons. A first idea to explore is to use deep learning to predict if segments should be merged, and then use biological constraints to identify biologically plausible groupings based on the deep learning results. Coding will be done in Python, using Theano and Pylearn2 as deep learning libraries. The data is already acquired and we have sufficient manual annotations for deep learning.
Keywords: Deep learning, Python, Theano, Connectomics.
 
**Synapse detection for Connectomics**:

We are interested in using computer vision approaches to detect synapses in electron microscopy images of mammalian brain tissue. While neurons can be seen as the wires of the brain, synapses are the contacts that define the actual circuit, and thus are crucial in gaining insights into the functional structure of the brain. While state of the art methods for synapse detection use random forests and boosting on hand designed features to classify each pixel in the images, we want to explore deep learning methods for this purpose. Coding will be done in Python, using Theano and Pylearn2 as deep learning libraries. The data is already acquired and we have sufficient manual annotations for deep learning.
Keywords: Deep learning, Python, Theano, Connectomics.
 
 

###Hotel Price Prediction and Sentiment Analysis

Bryan Balin, *SmarterTravel**

Hotel price prediction:We capture pricing data on thousands of hotels (and room types) each day, creating quite an extensive dataset.  With this data, we’d like to have a feature on Hotel Watchdog (http://www.airfarewatchdog.com/hotels/) that tells the customer the probability of whether the price for that hotel and room type is likely to go up or down over the next 7 days.  There is a great deal of seasonality and city-level effects on hotel data, so the big challenge here is being able to make predictions given hotel prices tend to move abruptly in a way that resembles a step function.  Students could either try to make predictions at the city level, hotel star level within a city, hotel level, or room level within the hotel, depending on the quality and quantity of the data.

Sentiment analysis: We tend to favor surveys where users give free-form answers to questions, rather than channel users to a particular set of responses we expect out of them.  While it helps ward off response bias, we are often forced to just read a sample of the total results due to their sheer volume.  So, we would like students to text mine the responses (of which there are roughly 48,000 unique responses in our most recent survey) to five questions, and pull out simple binary information (was the response positive or negative?) as well as the themes of the response (was it about the quality of our customer service? Was it about the quality of the hotel? Was it about pricing?).  Part of the challenge here will be that you can have multiple themes per response, and each theme can be either positive or negative.  Extra kudos here would be given for a system that automatically determines which themes are in a response, rather than having us pre-set themes and make classifications on them. `

###Understanding subscription cues at the Boston Globe

Meredith Kokos, Peter Doucette , Thomas Brown, Angus Durocher; *Boston Globe*

The typical cyber-life of a  BostonGlobe user starts with anonymous visits- from casually visiting the site, to ultimately becoming a subscriber. The BostonGlobe would like to understand the idiosyncrasies and patterns of a subscriber and use that knowledge to increase subscriptions.  
The goals of this project is to develop predictive models for the subscription process using web transaction data from the BostonGlobe.com and Boston.com. The data includes pages visited, click-throughs, time of visits, frequency of visits and other contextual information of these users as they pass through the sales conversion funnel.
Students will be given data for a set of users that have become subscribers and data on users that have remained anonymous. By extracting features from these longitudinal data and cross-correlating transaction events with other local or global events, students will develop models  and evaluate them on a subset of this dataset (testing subset). The final product will be a model and a post-mortem probabilistic characterization of the types of uses: the result will be a measure of the probability of becoming a subscriber at a given time. 

###Query Based on Distances of 3D Objects in Large Volume Data

Johanna Beyer, *SEAS*

Problem:

We have very large volume and segmentation data and would like to a) visualize it with interactive framerates and b) evaluate different kind of queries on the data, often based on distances or locations of objects in 3D

Overall goal of interactive queries:

We want to allow neuroscientists to analyze their connectomics data (extremely large EM data and their segmentation) at interactive rates. So that they can interactively explore the data, evaluate queries, and find patterns.

Idea:

We want to use an octree of min/max values for the EM (electron microscopy) data, which can be used for empty space skipping (to speed up rendering).
We also want to use an octree of objectID histograms for the segmentation data, which can be used for empty space skipping as well as for interactively computing distance queries.
For the segmentation data we probably need two different kinds of objectID histograms: 1) histograms that represents the objectIDs in each block of the octree (say each block in the octree is $32^3$, then the histogram of that block would contain $32^3$ entries) 2) a histogram, that is actually more like a complete list of segmentationIDs, that stores ALL object IDs that are in the spatial extent of the octree block (but in its highest resolution). So this will be a rather long list for lower resolutions.

Work:

For the final projectwe could focus on different octree traversal algorithms for computing the results of these queries interactively. Examples would be: 1) Which objects are in a certain spatial region of interest? (This one is already implemented for cubes, spheres and ellipsoids). 2) What is the minimum distance of 2 objects in the volume? 3) What are all objects that are in the vicinity of a certain object? etc.
For the project, we will first focus on implementing the actual agorithm in our own framework, maybe with fake data, and then, if time allows, incorporate it into the actual framework.

###Averaged Implicit SGD

Edoardo Airoldi, *Stats*

Stochastic gradient methods have increasingly become popular for large-scale
optimization. However, they are often numerically unstable and statistically
inefficient because of their sensitivity to the problem convexity and learning
rate specification. We propose a new learning procedure, termed averaged
implicit stochastic gradient descent (AI-SGD), which combines stability through
proximal (implicit) updates and statistical efficiency through averaging of the
iterates. In an asymptotic analysis we prove convergence of the procedure and
show that it is statistically optimal, i.e., it achieves the Cramer-Rao lower
variance bound. In a non-asymptotic analysis, we show that the apparent
stability of AI-SGD is due to its robustness to misspecifications of the
learning rate with respect to the convexity of the loss function. Our
experiments demonstrate that AI-SGD performs on par with state-of-the-art
learning methods. Furthermore, AI-SGD is more stable than averaging methods that
do not utilize proximal updates, and it is simpler and computationally more
efficient than methods that do employ proximal updates in an incremental
fashion.