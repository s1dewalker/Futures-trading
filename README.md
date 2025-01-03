![](Screenshots/FTS3.jpg)
<br/>
"There is one attribute that stands out above all: **consistency**" <br/>
 It's a process. <br/>

# **DATA ANALYTICS W/ EXCEL**
### LIVE OVERVIEW DASHBOARD - Keeping an Eagle Eye on Australian Fixed Income market

![](Screenshots/DB4.PNG)
<br/>
*STIR: 30-day Interbank Cash Rate Futures, 90-day accepted Bill Futures, their spreads, flies, de-flies, condors, other combinations and curve structures.* <br/>
*BONDS: 3-year bond, 10-year bond, yield curve.* <br/>
*Creating this dashboard helped to view the entire Australian Fixed Income futures market in one screen.*
<br/><br/>

### RISK SCENARIO ANALYSIS - Look at the Range of Outcomes and Be Prepared for it 

![](Screenshots/sa2.PNG)
<br/>
*Case scenarios for front contracts | Meeting impacts on contracts | Contract ranges | Curve movement | Risk-reward ratio* <br/>

*This helped to input basis point expectations for each RBA meeting and check the pricing for different cases, which gave ranges, risk-reward for contracts and combinations. Bottom left side had meeting impact section, which showed meeting impacts on the selected contract or strategy.* <br/> *This showed which trades not to take, more than, which trades to take.* <br/>

*"Sometimes, not taking a trade is a trade itself."*
<br/><br/>

### PERFORMANCE ANALYSIS - Changing the Game with Metrics and Stats
![](Screenshots/pa_final.JPG)
<br/>
*Analyzing different setups and contracts | Net PnL, Participation and Lot sizing <br/>
Wins vs Losses | Viewing wins & losses objectively* <br/>

*Separating wins and losses helped check the nature of trading strategies objectively. This helped to be defensive on losing (or, not so profitable) strategies and push on the better ones, improving consistency.*
<br/>

*Consistency is not just about making profitable trades every single time. It is about growing a discipline approach to trading that generates reliable results over a long period of time.* <br/>

*__Consistency focus:__* <br/>

- *Market analysts focused on consistency prioritize the reliability and stability of their performance over time. They aim to generate steady returns while minimizing the impact of losses and market volatility.*
- *While consistency focused analysts may not always achieve the highest returns on individual transactions, they aim to maintain a steady and reliable track record of profitability. In turn such an approach can lead to more predictable and manageable outcomes over the long term.*

<br/>

### AUTOMATED TRACKING FI METRICS<br/>

<img src="Screenshots/macrobp.png" alt="Description" width="800">

<img src="Screenshots/macromet.JPG" alt="Description" width="800">

*Automated recording metrics like expectations for the next 10 RBA meetings, yield curve, terminal rate, around volatile events using Excel Macros.* <br/>
<BR/><BR/>

# QUANTITATIVE ANALYSIS (QA) & MODELS<br/>
### Statistical Analysis | Value at Risk (VaR) 

<img src="Screenshots/var.JPG" alt="Description" width="500"> 

#### [View Python code for statistical analysis](https://github.com/s1dewalker/Futures-trading/blob/main/Stats.ipynb)  

### Random Walk Simulation for Simulation VaR

<img src="Screenshots/monte_carloSim.JPG" alt="Description" width="500"> 

#### [View Monte Carlo Simulation](https://github.com/s1dewalker/Futures-trading/blob/main/Quantitative-Analysis-(QA)/A_random_walk_simulation.ipynb)

### Correlation
<img src="Screenshots/correlation_24.JPG" alt="Description" width="500">

### Machine Learning (k-means clustering) to find market states 
#### [Finding states w/ clustering in Python](https://github.com/s1dewalker/Futures-trading/blob/main/Quantitative-Analysis-(QA)/qtnb3-states.ipynb)

Steps: <br/>
1. Data preparation: cleaning, transformation <br/>
2. Create features: like high-low, hl/volume, 5 day rolling volatility, etc and get them in a separate dataframe "X"
3. Normalize "X" (as some features might dominate due to larger scale): use `MinMaxScaler` function
4. Find market states w/ k-means clustering: find best "k" with WCSS method with `inertia_`. Fit the model with `KMeans`. Predict clusters with `.fit_predict` on "X".

### Simple Markov Model to predict market states

<img src="Screenshots/mtm.JPG" alt="Description" width="500">

*Applications:* <br/>
- *Prediction: Predict the next state of the market based on the current state (i.e., forecasting the market's behavior).*
- *Optimization: Use the Markov Model for portfolio optimization, where states represent different market conditions, and transitions model how the market shifts.*
- *Risk Assessment: Assess the risk of being in a certain state at a future time.*

#### [View Model in Python](https://github.com/s1dewalker/Futures-trading/blob/main/Quantitative-Analysis-(QA)/MARKOV_MODEL_2.ipynb)

<br/>

### Trade Journal<br/>

<img src="Screenshots/TJ2.JPG" alt="Description" width="800">

*Maintaining a journal for events, trade setup, risk management, worst case losses, PnL, observations, perceptions, and strategy updates.* <BR/>
***Knowing the risks before taking them.*** <br/>
*[View Trade Journal Analysis in Python](https://github.com/s1dewalker/Airbnb-listings-NYC/blob/main/Airbnb%20correlation.ipynb](https://github.com/s1dewalker/Futures-trading/blob/main/trade_journal_analysis/tja.ipynb))* <br/>

<BR/><BR/>
# RESILIENT AND DEFENSIVE ACCOUNT MANAGEMENT SYSTEM<br/>
*Balance sheet was mostly Conservative and Risk Averse.*

- #### Lot sizing
<img src="Screenshots/lot_sizing.JPG" alt="Description" width="800">

- #### Allocation
<img src="Screenshots/allocation.JPG" alt="Description" width="800">

<BR/><BR/> 

# RESULTS
![](Screenshots/pat23.PNG)

<br/><br/>

*hope you find it helpful, and encourage you to forward any suggestions for improvements* <br/>
##### [LinkedIn](https://www.linkedin.com/in/sujay-bhaumik-d12/) | s1dewalker23@gmail.com | [Discussions](https://github.com/s1dewalker/Futures-trading/discussions/1) | [Research Works](https://github.com/s1dewalker/Research-Works)
