# Prediction Market Manipulation Papers

## "How manipulable are prediction markets?" (2025)
[Link](https://arxiv.org/html/2503.03312v1)
[GitHub](https://github.com/Itzhak95/prediction_markets_model)
Authors: Itzhak Rasooly, Roberto Rozzi

**Main research question:**

*Can a single actor use a large sum of money to manipulate a precition market?*

**Main takeaway:** 

*How the f\*\*\* did this get IRB approval.*

This paper is a great experiment on how an actual measured price shock can affect a market, and the conclusion that this can have a long lasting affect on the market, even though it does tend to trend back towards the actual value. So it helps point to these manipulations being possible in practice, which makes it a good basis for future research.

For the ethics part, this might be a good example of what to think about when doing an experiment. I think it would be better to aim for an observational experiment either on current or historical prediction market data. Another direction, that can be in addition to an observational study, would be to "wargame" the situation and just explain some plausible ways market manipulation can be done on platforms like Polymarket and Kalshi for financial or political gain.

Related Articles:
- [Information aggregation and manipulation in an experimental market](https://www.sciencedirect.com/science/article/pii/S0167268105001575)
- [How the presence of an unpredictable manipulator makes the market more attractive to informed traders](https://drive.google.com/file/d/0B8HWJBMsuhgFcS05TllkR3VrUUU/view?resourcekey=0-zt2HOtytur68FpeXWyw5Sg)

## "Manipulation in Prediction Markets: An Agent-based Modeling Experiment" (2026)
[Link](https://arxiv.org/html/2601.20452v1)
[GitHub](https://github.com/ebbam/power_prediction/)
Authors: Ebba Mark, Bridget Smart, Anne Bastian, Josefina Waugh

**Main research question:**

*Under what conditions do contemporary prediction markets function as self-correcting information processing mechanisms, and when can they instead temporarily sustain price deviations introduced by a highly resourced, biased minority?*

**Main takeaway:**

*For an action to meaningfully introduce error, it requires above 30% of total market capital. A price distortion can provide meaningful profit gain to high expertise traders who can take advantage of the temporariliy misaligned price.*

This paper has a great simulation showing how market manipulation could occur at a large scale. The idea of simulating some of these strategies through an Agent-based modeling framework is interesting (Using something like MESA which I have experience in.) It also showed how for these manipulations to have a substential effect, they have to be considerably large, usually over a third of the market capital.

One thing is that this paper focused on simulating "whale" accounts, I do wonder about how a "bot-net" would function, where instead of one account putting in millions of dollars, you have thousands of accounts putting in thousands of dollars over a period of time, which could appear less suspicious.

I am generally interested in this idea of "laundering" obvious market manipulation to make it seem more innocent.

Related Articles:
- [How manipulation can be rapidly corrected](https://link.springer.com/article/10.1007/s10796-015-9617-7)
- [Stock manipulation modeling for comparison](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4863876)
- [Friedman self-correction mechanism, in theory](https://web.stanford.edu/~avner/Greif_228_2005/Friedman%201953%20Methodology.pdf) Note that this widley agreed in economics to be "correct" in theory, but that the market conditions that must exist for it are definitly being constantly violated in reality.

## "Affecting policy by manipulating prediction markets: Experimental evidence" (2013)
[Link](https://www.sciencedirect.com/science/article/pii/S0167268112002223)
Authors: Cary Deck, Shengle Lin, David Porter 

**Main research question:**

*Are prediction markets robust to manipulation attacks, meaning they can be used to improve forcast accuracy without worry, or can they be manipulatated in a way that destroys the market's ability improve forcasting.*

**Main takeaway:**

*A single-minded, well-funded manipulator can destory a prediction market's ability to aggregate informative prices and mislead those who are making forcasts based upon it. But, this cannot change the bids and asks element of a prediction market.*

This paper is a great "foundational" paper talking about the limits of manipulation. Specifically, it points out how manipulating a market can only really be done to the *transaction price stream*, meaning the trades that actually go through. They cannot easily corrupt the information in the *order book*, which are limit orders that traders have placed but have not yet executed (such as saying I'll buy when the price reaches 40 cents, or I'll sell at 52 cents.)

The order book can show a much better picture of what traders believe, even if the actual transactions have been manipulated. The order book is much more expensive to corrupt, because you would have to fill all of those orders. So a forcaster can still look at the order book to recover a more accurate picture of what the market believes.

This disconnect between the order book and price due to manipulation is somewhat measurable, and could be an interesting thing to look into. It is well studied in finacial markets, and for measurment there is **PIN** (probability of informed trading).

The order of development for measurement was Kyle's Lambda in 1985, PIN in 1996, and VPIN in 2012.

Related Articles:
- [About PIN](https://frds.io/measures/probability_of_informed_trading/)
- [Limits of PIN](https://onlinelibrary.wiley.com/doi/full/10.1111/1540-6261.00493)
- [More Limits of PIN](https://www.sciencedirect.com/science/article/pii/S0378426621000030)
- [Using Kyle's Lambda and VPIN](https://link.springer.com/article/10.1007/s10796-015-9617-7)
- [Kyle's Lambda](https://www.econometricsociety.org/publications/econometrica/1985/11/01/continuous-auctions-and-insider-trading)
- [VPIN](https://academic.oup.com/rfs/article/25/5/1457/1569929?guestAccessKey=)