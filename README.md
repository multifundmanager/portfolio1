# portfolio1 - keep investment track record - NOT investment advice
I'm creating this github project to track my investment portfolio and create a publicly available investment record. Github allows anyone to audit the history of my updates to the files in this project, which means I don't have a way of updating my investment decisions after I've made them.

**The information here should NOT be considered investment advice. If you need investment advice, you should seek it from a qualified professional, based upon your investment goals and risk tolerance.**

The portfolio I'm tracking here has a high risk profile, with the main objective of maximising alpha. I'll benchmark it against several "adventurous" worldwide portfolio, including both buy-and-hold and monthly-investment strategies to simulate "passive" investors who allocate their money as a one-off and more "active" ones who keep on investing on a monthly basis. All prices are taken from morningstar.co.uk and reflect information such as dividends and some but not all fees (see morningstar.co.uk for more precise information). 

In choosing my investments, I'm taking the view of someone based in the UK. Returns would of course be different if I were based somewhere else because of currency fluctuations. My portfolio however is structured specifically with the goal of maximisising the profits of a UK-based investor, and would certainly look different without this assumption.

The main file is investments.csv. The way to read is is that for each date for which I'm specifying a position, I would buy/sell what's required to match it. So for instance if on day 1 I have this

Fund1 30%
Fund2 70%

And on day 30 I have this

Fund1 40%
Fund2 60%

And assuming they have grown at the same pace, then I would sell a part of Fund2 and buy Fund1 with the proceedings. Of course it may well be that Fund1 has grown more than Fund2, to the point of already matching my target position or even outstripping it. Between dates, the assumption is that I won't touch my portfolio, regardless of how much the actual position drifts away from my target one. I'll report all these calculations in Excel files, but keep investment.csv in text format so it's easier to compare its history directly in github.

As already mentioned, I'll calculate performance for both a scenario where I buy and hold (apart from changes to match my target position) and for a scenario where I buy each month around the 10th.

Further note: both the benchmark and my portfolio are selected from Fidelity UK. The whole set of available funds can be see here https://www.fidelity.co.uk/investing/investment-finder. I have no relationship with Fidelity other than being a customer and I am in no way endorsing Fidelity.

The benchmark I'm using is the GBP world equity fund from Fidelity, since it uses the same asset type and currency that I do and is well diverified across geographies, sectors etc, which is also the kind of strategy I'm adopting. In particular, I've chosen GB00BJS8SJ34 - Fidelity Index World P Acc, which at the time of writing has 4 stars on Morningstar.