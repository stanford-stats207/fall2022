---
layout: default
title: Projects
nav_order: 5
---

## Important Dates
* Mon., Oct. 24 at 11:59pm: Project Proposals 
* Mon., Nov. 14 at 11:59pm: Project Milestone  
* Weds., Dec. 7 from 1:30-3:00pm: Poster Session (Sequoia Hall Courtyard)
* Weds., Dec. 14 at 11:59am (yes, am): Project Report [GRADES DUE DEC 20]

## Your Course Project 

Your class project is an opportunity for you to explore an interesting time series problem in the context of a real-world data set. We are providing some seed project ideas below. You can pick one of these ideas and explore the data and algorithms within and beyond what we suggest. You can also use your own data/ideas, but, in this case, you have to make sure you have the data available now and a nice roadmap, since a quarter is too short to explore a brand new concept.

Projects can be done by you as an individual, or in teams of two students. You can discuss your ideas and approach with the instructors, but of course the final responsibility to define and execute an interesting piece of work is yours.

The final project is worth 40% of your grade, which will be split amongst four deliverables:
* A project proposal (feedback, but no grade), due on October 24th by 11:59pm.
* A project milestone (10% of the final grade), due on November 14th by 11:59pm.
* A project poster presentation (10% of the final grade), on December 7th from 1:30-3:00pm (class time) in the Sequoia Hall Courtyard.
* A final report (20% of the final grade), due on December 14th by 11:59am (yes, am).

Your project will be evaluated by three criteria:
* Technical Depth: How technically challenging was what you did?
* Scope: How broad was your project? How many aspects, angles, variations did you explore? 
* Presentation: How well did you explain what you did, your results, and interpret the outcomes? Did you use the good graphs and visualizations? How clear was the writing?

The Technical Depth and Scope are complementary criteria, e.g., if you develop a single elaborate algorithm or model on a small dataset, you may score high on depth but low on scope, while if you try many very simple methods on different datasets, your scope would be higher but the depth lower. 

To give you a sense of what we're expecting:
* A **great project** would involve constructing a model---one that synthesizes and goes beyond the various ideas from lecture and homework---tailored to your particular dataset and careful thought about how to perform your statistical analyses. It would involve a variety of analyses to check your model and justify your interpretation of the results. The presentation would clearly and concisely convey your results.
* An **okay project** would tweak a model, algorithm, and analysis from class and apply it to a new dataset. It would involve a few different checks to show that the model is appropriate and a nice report of your findings. (A better project would consider a range of modeling or algorithmic approaches and thoroughly study which performed best, and explain why.) The presentation would get the message across.
* A **subpar project** would simply apply existing techniques from scikit learn, RStudio, Stan tutorials, etc. to a dataset and do the bare minimum to get a result.  The models and algorithms would have been covered in lectures or homeworks with the dataset considered not requiring any new insights.  It might omit key steps of model checking and model criticism or have clear conceptual errors in the model and/or algorithm formulation. The presentation might be perfunctory.

 
## Project Proposal  

You must turn in a project proposal on **October 24th by 11:59pm via Gradescope**.

Read the list of available data sets and potential project ideas below. If you prefer to use a different data set, we will consider your proposal, but you must have access to this data already, and present a clear proposal for what you would do with it.  

**Project proposal format**: Proposals should be **one page maximum**. Include the following information:
* Project title
* Data set
* Project idea. This should be approximately two paragraphs.
* Software you will need to write.
* Papers to read. Include 1-3 relevant papers. If you are doing something different then one of the suggested projects, you will probably want to read at least one of them before submitting your proposal.
* Teammate: will you have a teammate? If so, whom? Maximum team size is two students. One proposal per team.
* Milestone: What will you complete by the milestone? Experimental results of some kind are expected here.
 
## Project Milestone  

A project milestone should be submitted on **November 14th by 11:59pm via Gradescope**. Your write up should be **3 pages maximum** in [NeurIPS format](https://nips.cc/Conferences/2020/PaperInformation/StyleFiles), not including references (the templates are for LaTex, if you want to use other editors/options please try to get close to the same format). You should describe the results of your first experiments here. Note that, as with any conference, the page limits are strict! Papers over the limit will not be considered.
 
## Poster Session  

We will hold a poster session on **December 7th from 1:30-3:00pm in the Sequoia Hall Courtyard**. Each team will be given a stand to present a poster summarizing the project motivation, methodology, and results. The poster session will give you a chance to show off the hard work you put into your project, and to learn about the projects of your peers. 

Here are some details on the poster format:
- We will provide poster boards that are 40” (height) x 30” (wide). 
- Suggested ways to make your poster:
   - Create a bunch of presentation slides (using powerpoint, beamer, etc), and print out each side on a piece of letter-sized paper. Then, put them all together on the provided poster board.
   - If you have access to a poster printer, you are welcome to create a single huge slide and print it out on a poster printer. However, you are not expected to have access to a poster printer, and you will not receive extra "presentation points" if you use this method.
 
## Project Report  

Your final submission will be a project report on **Wednesday, December 14th at 11:59am (yes, am not pm) via Gradescope**. 

Your write up should be **8 pages maximum** in [NeurIPS format](https://nips.cc/Conferences/2020/PaperInformation/StyleFiles), not including references (the templates are for LaTex, if you want to use other editors/options please try to get close to the same format). You should describe the task you solved, your approach, the algorithms, the results, and the conclusions of your analysis. Note that, as with any conference, the page limits are strict! Papers over the limit will not be considered.
 
## Project Ideas  

The course staff has outlined several potential project ideas below. This should give you a sense of the datasets available and an appropriate scope for your project. **You can either pick one of these or come up with something of your own to work on**.

### Idea 1: Neuroscience

(Neural Dynamics and Functional Connectivity) In addition to studying neural dynamics, a large research area in neuroscience is understanding how neural systems interact with each other. This is useful in understanding the pathways involved when the brain executes a complex task. Given time series data about the activity in each region of the brain, for example, EEG data or functional MRI data, how can you determine which signals in a certain system affect other signals in a different region of the brain? Granger causality is a way of inferring lagged, directed connections between regions.  Graphical models can uncover instantaneous, undirected connectivity.  A project here would be to learn about these types of methods and apply them to a neuroscience (or other proxy) dataset.

* Datasets: https://www.ieeg.org

* Background references:
   - https://www.sciencedirect.com/science/article/pii/S0959438818301570?via%3Dihub
   - https://arxiv.org/abs/2105.02675

* Papers that are examples of the project ideas above:
   - https://arxiv.org/abs/1402.6951
   - https://arxiv.org/pdf/1802.05842.pdf
   - https://www.tandfonline.com/doi/full/10.1080/01621459.2018.1476238


### Idea 2: Financial Time Series

**Project Ideas**

1. (**Price Forecasting**) Every trader's dream is to directly predict price movements: do basic time series forecasting methods have any predictive ability, perhaps on certain collections of stocks? Do they work for different asset classes? A project here would apply multiple models including ARMA / ARIMA forecasting, Kalman filters, LSTM, DL methods to attempt price prediction.

Additionally, a lot of empirical work in finance has uncovered peculiar behaviors of price return time series. Examples of these so-called ‘stylized facts’ include: heavy tailed return distributions, time varying (and persistent) volatility, slowly decaying autocorrelation function, and steady correlations between certain asset classes (like stocks and bonds). Perhaps a famous example is the equity risk premium (which is why the broader market has consistently positive returns). Another aspect to consider is replicating these observations using basic time series methods; do your methods for price prediction need to adapted in light of these empirical facts?

Caveat: this problem is known to have very high signal-to-noise ratio and blindly applying an array of time series methods will not result in an interesting project. We recommend finding a specific hypothesis to test before choosing a project based around price forecasting.

2. (**Stochastic Volatility**) Practitioners also care a lot about forecasting volatility, which is the variance of stock prices. Higher volatility is useful for financial institutions as trading during those periods can mean increased opportunities; it also provides increased liquidity to exit out of large positions. Volatility is also intimately related with option pricing. A common time series model for volatility is the GARCH family of models.

 A project here would learn about and present GARCH modeling (which is a topic we have not covered in class), apply it to forecasting the variance of a certain asset, or other financial time series (stock price volatility, interest rates, etc). For example, fit an ARCH and GARCH model to your selected data. How does this compare to using methods we have seen in class, including ARMA models, state space models, etc?

3. (**Pairs Trading**) A certain strategy called pairs trading tries to capitalize on short term price dispersions between assets that should behave similarly. For example, stocks in the same industry selling similar products are expected to behave similarly, statistically speaking. When the prices diverge, you place a bet that they will eventually converge again and behave similarly. There are multiple ways of quantifying similarity between time series. For example, price difference / price ratio can be modeled by a stationary, mean reverting process, such as an OU process (a type of Gaussian process). A project here could be to identify such a pairs trade, fit an OU process model to it, and test whether the difference reverts to the mean frequently. Can you forecast the next reversion time? Another related project is to identify good pairs trades by statistical tests, such as Cross correlation, Cointegration, or Granger causality. You would learn about and apply these concepts to finding such trades. How do each of these methods compare for generating good pairs trades?


* Data dources: Google Finance, Yahoo Finance.

* References:
   - For price prediction:
      - https://thecleverprogrammer.com/2020/11/14/stock-price-prediction-using-machine-learning/
      - https://thecleverprogrammer.com/2020/08/09/stock-price-prediction-with-facebook-prophet-model/
      - A simple google search for ‘stylized facts’ will give several references.
   - For GARCH modeling:
      - See ch. 5 of textbook "Statistics and Data Analysis for Financial Engineering: With R Examples, Ruppert and Matteson". 
      - For a survey of GARCH usage in finance and econometrics, see "Garch 101: The use of ARCH/GARCH Models in Applied Econometrics, Engle 2001".
   - For pairs trading, the below articles provide an implementation overview of the strategy. There are also academic papers linked within these sources.
      - https://quantpedia.com/strategies/pairs-trading-with-stocks/
      - https://hudsonthames.org/an-introduction-to-cointegration/
      - https://hudsonthames.org/optimal-stopping-in-pairs-trading-ornstein-uhlenbeck-model/


### Idea 3: Environmental Data

**Project Ideas**

1. (**Air Quality Index data**)  The Air Quality Index is a measure that is important not only in California but in other large metropolitan areas with high smog rates. It’s important to forecast the air quality index in a specific location, say Santa Clara county, so that at-risk populations can prepare. Can you use the time series models we studied in class to forecast AQI? How would you incorporate the spatio temporal aspect of the data? Using AQI data in adjacent locations might help in time series forecasting; how would you incorporate this in your model? Can you use other information such as wildfire data or weather data to help forecast AQI?

2. (**Global Temperature Forecasting**) The IPCC released an unequivocal 2021 report on the human impacts on global warming: there is little doubt that the past century of unprecedented warming  has been a result of human activity. Using historical temperature data, can basic time series methods quantify how unusual the past century of warming has been? Another aspect of the project is to forecast temperatures beyond the current year; can these be improved using auxiliary data such as human industrial activity, carbon emissions, or certain weather patterns like El Nino? How do your methods compare to the estimates given in the IPCC report; do they improve those predictions in any way? 


* Data sources:
   - https://www.epa.gov/outdoor-air-quality-data
   - https://climatedataguide.ucar.edu/climate-data/global-temperature-data-sets-overview-comparison-table

* References:
   - Intelligent modeling strategies for forecasting air quality time series: A review, Liu et al. 2021
   - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6164777/


### Idea 4: Epidemiology

**Project Ideas**

1. (**Flu prediction**) Can you forecast flu trends by fitting certain time series models? What additional data can you augment which could help in this task? For example, flu trends from adjacent countries, vaccination rates, internet searches, etc.

One interesting baseline for comparison is the Google Flu trends project, which was the subject of a high profile failure of big data forecasting. Forecasts for the 2013 flu season were so inaccurate that Google decided to shutter the project in 2015. You can try finding this data on google datasets, or potentially attempt to recreate this using Google trends. One aspect of the project is to see how your model compares to Google’s model, and to see if there are similar limitations. Are these limitations inherent in basic time series methods? What modeling techniques or analyses would you need to use to not make these mistakes?


2. (**COVID modeling / prediction**) How well can various time series methods forecast COVID cases?  What are the strengths and limitations of the various approaches?  Is it possible to estimate the impact of COVID restrictions on COVID cases, for example, by comparing countries where one imposed restrictions, while the other did not.


* Datasets:
   - https://covid19forecasthub.org/data/
   - https://predict.cdc.gov/
   - https://covidtracking.com/analysis-updates/federal-covid-data-101-how-to-find-data
   - https://www.cdc.gov/flu/weekly/usmap.htm

* References:
   - Reappraising the utility of Google Flu Trends, Sasikiran Kandula, Jeffrey Shaman
   - Bayesian Nonparametric Covariance Regression, Emily Fox, David Dunson

* Covid time series papers / projects:
   - https://towardsdatascience.com/predicting-number-of-covid19-deaths-using-time-series-analysis-arima-model-4ad92c48b3ae
   - https://www.medrxiv.org/content/10.1101/2021.04.24.21255827v1
   - System for Forecasting COVID-19 Cases Using Time-Series ...https://www.mdpi.com › pdf
   - https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0244173
   - https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0245414
   - https://www.sciencedirect.com/science/article/pii/S1477893920302210
   - … (many, many, many such papers.  Above not thoroughly vetted)
