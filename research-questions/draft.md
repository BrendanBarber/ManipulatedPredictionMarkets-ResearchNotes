Overall Idea: *How could public prediction markets (such as Polymarket/Kalshi) be manipulated by bad actors for political gain, using a combination of traditional market manipulation methods and misinformation and disinformation?* 

This recent paper looks at purely financial means of manipulation, using Agent-Based Modeling: [Pre-print paper](https://arxiv.org/pdf/2601.20452) *This paper does ABM in a very closed system, where the only information available is some level of external confidence in the outcome, and the market itself. Public opinion in their model is exogenous. This could be expanded to also model some of the external information flow ('true' information/misinformation/disinformation)*

This sociotechnical-focused paper looks at the inaccuracies and flaws of modern prediction markets: [Pre-print paper](https://arxiv.org/html/2602.05181v1) *This paper isn't about the modeling part, instead it acts as the motivation. Their core claim a about 'Prediction Laundering'. They show how Prediction market prices are increasingly being treated by the media as an authorative source of public opinion and expert opinion. This authority is illusory, because the price is a product of capital asymmetry.*

My goal, and why this matters: *Rohanifar et al. identify the laundering process qualitatively; I formally model that mechanism by which one specific kind of dirty input gets converted into a clean looking signal, and I focus on the actual cost and persistence of that conversion.*

**Draft Research Question:** *How do the cost and persistence of prediction market manipulation change when a manipulating agent can also expend resources to influence the public opinion signal that affects other agents?*

*Notes on this research question:*
1. Can a combined manipulator (direct manipulation and misinformation/disinformation) achieve a more persistent change for a lower cost?
2. What is the optimal split?
3. This model can compare to that other papers model (as well as other ABM of prediction markets)
4. Does the decay of distortions take longer or not decay at all if public opinion is also shifted?
5. The key feedback loop can be modeled, where the market price itself can be the news and change the public opinion.
6. Under what parameters does the system have a stable manipulated equilibrium? Where does it run away, and where does it self-correct?
7. Future ideas: Using this model to find patterns for detection.

*Some important notes on ABM*
1. In agent-based models, it is easy to just tune the parameters to get what you want.
2. Because data on Polymarket is public and there are studies on social media propogation, use those to try and ground the model.
   1. Market depth/liquidity (Polymarket)
   2. Trader budget distribution (Polymarket)
   3. Opinion changes (Twitter cascade data?)
   4. Disinfo reach per dollar (Graphika?)
3. The claim can be qualitative and not depend on the parameter values, such as saying that "Persistence is superadditive, combined manipulation last longer than the sum of single-channel manipulations of the same total cost."
4. How do we measure the cost of the opinion channel?
5. Persistence has to be defined, one possible option is "Distortion at resolution time." Since these markets have an "ending point", any distorition after this point has no value.

Another important takeaway: *Cost-efficiency of manipulation matters because as these markets get more popular, they also get much more expensive to directly manipulate. In theory, this insulates the most important from being directly manipulated.*

A qoute from the Smart et al. paper of interest: *"Should there exist a potential channel through which a prediction market price could influence voting behavior... This work does not explore such an interaction."* That is partially the goal of my follow-up.

[Algorithm Market Manipulation](https://financelawpolicy.umich.edu/research-projects/algorithmic-market-manipulation) (Look at more [Wellman](https://midas.umich.edu/directory/michael-wellman/) papers)

And of course Hanson-Oprea papers on empircal market manipulation.
