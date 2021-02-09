# Model-for-Multiple-Dynamic-CPPI-Strategy
 
Portfolio insurance is a hedging strategy which allows investors to recover at maturity a given percentage of their initial investment. 
The Portfolio insurance strategy limits downside risk in falling markets, while allowing potential benefits in rising markets.
One of the most typical Portfolio insurance strategy is the Constant Proportion Portfolio Insurance (CPPI). 
This strategy is based on parameter setting with just only one parameter which is multiple (denoted by m) and operates as static strategies like stop-loss and buy-hold.
Multiple parameter m directly determines the risk exposure. In tradtitional CPPI, this parameter is fixed from the beginning, and doesn’t changes with the market conditions.
We reallocate the portfolio at the end of each period based on m. This strategy will not fail if re-allocation occurs continuously. 
But in practice, re-allocation cannot be carried out continuously, or even between a very short period because of transaction costs.
Our project focuses on the dynamic setting of the multiple m, which makes the CPPI strategy more stable with the changes of market but still benefit from growing market.
For building the model with multiple dynamic setting, we will use extreme value theory(EVT). 
Although extreme values scarcely happen in real data, we can use extreme value theory to obtain the entire shape of losses’ tail, which give a better fit for the distribution
of the loss.
In this report, we give some basic descriptions of the CPPI strategy and introduce the model for multiple dynamic setting of CPPI with an application of extreme value theory.
Then, for empirical studies, we will apply this model for CAC40 weekly data and compare the results with the traditional CPPI setting.

Done by Djiomou, Le Tung, Giang and Babou 
