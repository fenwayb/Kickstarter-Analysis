<h1 Align="Center">
  
  Kickstarter Analysis
  
  <i>Performing analysis on Kickstarter data to uncover trends</i>
  
    

  # Overview
  
  ### Purpose
  
  <p>The purpose of this project was to analyze kickstarter funding data to advise our client Louise on how to maximize the funding of her own theater kickstarters</p>

  ### Background
  
  <p>This dataset comes from kickstarters of many different categories and across multiple countries ran between 2009 and 2017. Louise's goal is to fund a theater play in the United States and potentially a theater musical in the United Kingdom so these were the main categories/regions focused upon</p>
  
  # Analysis and Challenges
  
  <p>Throughout this project the data was analyzed through multiple different lens to identify potentially useful trends. During this process there were also challenges that were faced with adapting certain parts of the data set to glean useful information out of it for our theater purposes.</p>
  
  ### Analysis
  
  <p>Various Analyses were ran on the dataset. We looked at how likely kickstarters were to be successfully funded based on which month they were started in. We also looked at the percentage of projects that were funded based on their goal amount</p>
  
  ### Challenges
 
  ![Gaming example](https://user-images.githubusercontent.com/106105597/175459741-d5fafde3-5831-4d8a-83cf-2095a4f545e2.png)

  <p>One challenge that comes up when comparing our desired kickstarters to kickstarters of other categories is that funding habits can be drastically different by category. In the above example it can be seen that there were no US tabletop gaming kickstarters that failed to reach their funding goals over the dataset and conversely there was not a single successful US video gaming kickstarter during that time. While this can still be useful to analyze (and is touched upon in the results), this just means that there is less data to be able to compare.
    
  ![outliers](https://user-images.githubusercontent.com/106105597/175462241-c5746ce2-91cc-452c-b7c4-e808d3742856.png)

  Another Challenge that was faced were outliers. This is less of a problem when analyzing the kickstarter goals but when analyzing what actually ended up getting pledged the data was largely skewed left. This is likely because kickstarters can become popular and blow past their original funding goals, making significantly more money than they set out to make. While this is not the norm as can be seen by the boxes being fairly close between goals and pledged, it clearly happens often enough and dramatically enough that it can skew the data.</p>

  # Results
  
  <p>Overall it seems as if we found some impactful factors that Louise should keep in mind when starting her kickstarter. These factors are visualized in the following graphs. </p>
  
  ### Theater Outcomes by Launch Date
  
  ![Theater Outcomes Based On Launch Date](https://user-images.githubusercontent.com/106105597/175458297-69fddeb1-713a-475b-8417-7df899207a6e.png)
  
  <p>This graph shows how many theater kickstarters were successful/failed/cancelled based on which month they were started in. It seems as if kickstarters get cancelled and to a lesser extent fail at somewhat similar rates throughout the year. Both of those outcomes also occur at lesser rates than successes, which is great news for Louise. The most important conclusion to draw from this graph is the spike in successes between the months of May and July. Starting her funding during these months would give her the best chance of reaching her funding goals</p> 
  
  ### Outcome based on Goals
  
 ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/106105597/175458340-7cf7f1ac-89e4-40a8-997a-f8c18ded593e.png)

  <p>This graph shows the outcomes of all kickstarters based on what their original goal was. It seems as if keeping your funding goal below $15,000 gives you at least a 50% chance of reaching your goal. In the mid ranges the most likely outcome is failure. On the highest end of goals there is a sharp rise in failure and cancelling with corresponding sharp drop in successes. The good news for Louise at least is that kickstarters can go well past their funding goals so setting her goal conservatively does not prevent her from raising beyond that goal.</p>
  
  ### Final Thoughts
  
  <p>While this dataset was large it was not clear if it was an entirely inclusive dataset or just a sampling of this range of years. The years themselves are also a limitation. For instance the problems mentioned regarding the lack of failed US tabletop kickstarters or successful US video gaming kickstarters might potentially be resolved over a longer time period as more data points could be taken. An additional graph that could be made for this would be analysing the differences in funding across countries. Especailly as she wants to fund a musical in Great Britain in the future  </p>
