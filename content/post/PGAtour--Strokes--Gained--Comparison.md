---
title: "Comparing Strokes Gained Performance of golfers over many PGA Tour Tournaments"
description: "Taking a look at what separates golfers who make the cut, finish top 10, and come away with the win using SG data from 2020 PGA Tour Tournaments"
date: 2021-10-28T08:03:00-05:00
draft: false
categories: Golf
---

#### by Mallet James

Mark Broadie's strokes gained approach has given golf fans a way to appreciate the finer details of the game at a deeper level. In the past, golf fans and players alike needed to rely on somewhat arbitrary statistics to evauluate play. Hitting a fairway or green in regulation is always nice but what about the guy who tops 14 balls off the tee and still finds a way to hit the front of 10 fairways? The guy he's playing with who pipes his driver  14 times but narrowly misses a few fairways could have the exact same number of fairways hit, a flawed metric. The same goes for hitting a green in regulation. For an amatuer golfer, hitting it anywhere on a green for a GIR is usually good enough, that doesn't cut it though for the best in the world. Hitting a 150 yard shot into a green to 6 feet is a lot different than hitting the same shot to 15 feet and should be counted as such. The difference between hitting a green and not hitting a green or hitting a fairway or not is far too arbitrary to carry any meaning for PGA tour golfers which is where SG comes in. 

If a PGA Tour golfer is playing a tough par 4, based on past data it may have taken all golfers who played it an average of 4.2 strokes to finish that hole out. Strokes gained shines by allowing us to break down each piece of a golfer's game to figure out if they are an exceptional iron player but poor putter, incredible off the tee but struggling to hit it close to the pin from the fairway, etc.

Using past data on this imaginary par 4 that takes an average of 4.2 strokes to hole out we can see just how well a golfer performed on each shot compared to the rest of a field. A golfer may have hit a great drive to a spot where on average it took past players 2.7 shots to hole out. To calculate SG off the tee all you need to do is subtract the 2.7 strokes it takes on average to hole out from that position from the 4.2 shots that it takes on average to complete the hole to get 1.5 strokes, after subtracting your stroke (1 from your drive), you are left with .5 SG off the tee on that shot. Next you hit your approach shot to 30 feet, where according to PGA Tour website putting probabilities it takes an average of 1.977 putts to hole out, take the 2.7 (left from your drive) - 1.977 = 0.723 then subtract your shot and you see that you've lost .277 strokes on your approach shot (-.277 SG). Next up the 30 foot putt, you hole that one out and make a 3. A birdie on one of the toughest holes on the course is a huge plus but SG allows us to capture just how it happened. Since you've made the putt the strokes gained calculation is now 1.977 - 0 = 1.977 - 1 = .977. You gained .977 strokes on the field by making that 30 foot putt. To find total strokes gained on the hole we add up each shot .5 (SG off the tee) - .277 (SG approach) + .977 (SG Putting) to get a total of 1.2 strokes gained. Now instead of just knowing that we hit a fairway, hit a green, and made birdie we can see that we hit an above average drive, a poor approach shot, and an incredible putt. If we made par on that hole we would be quick to blame our missed approach shot but in this case we may forget all about it and credit how good our putt was to make birdie. This kind of give and take happens on nearly every hole during a round of golf. Strokes gained allows you to see just how well you performed on each shot versus the field. It gives you a clearer look into how the pieces of the game contributed to your scoring in any given round.

The capabilities of strokes gained is well documented in Mark Broadie's book Every Shot Counts, on the [PGA Tour website](https://www.pgatour.com/news/2016/05/31/strokes-gained-defined.html), and at datagolf.com where you could spend hours experimenting with the wide array of tools and analysis that they offer. Strokes gained can fluctuate as a raw number from tournament to tournament though which makes it tough to use for comparison. Garrick Higgo won the 2021 Palmetto Championship with a total SG of 3.08 and Charley Hoffman came in solo 2nd at the 2021 Valero Texas Open with a total SG of 4.15. Every course is different and every field is different so while raw strokes gained can tell us a lot about an individual golfer it is tough to compare the intracacies of many golfer's skillsets over many tournaments with raw strokes gained numbers alone.

To be able to compare for example, how approach SG has contributed to each player's game when each has played in 6 different tournaments we could look at raw strokes gained numbers and eyeball it. If one golfer has negative SG and another has well positive SG we would know right away that he is most likely the worse approach player but we have to wonder if he is playing in events with tougher fields, tougher conditions etc. To be able to get a better comparison of how much SG approach contributed to the game of each player we can take the percentage of the absolute total of strokes gained by that player that were SG approach. To illustrate the methodology I will break down the analysis using Jon Rahm's SG data from 12 random tournaments in 2020.

#### 2020 BMW Championship at Olympia Fields

| Golfer	      | SG Putt | SG ARG | SG APP | SG OTT | SG Total |
|-----------------|---------|--------|--------|--------|----------|
|Jon Rahm         | 0.97    | 0.35   | 0.75   | 0.75   | 2.82     |

This ends up being one of the easiest cases and an example of where my mind went first when considering taking each component of strokes gained as a percentage of total SG. Each SG value would be positive, making total SG positive and we have clean, meaningful percentages. In this case SG approach contributed to about 27% of Jon's total strokes gained. The hope was to continue the analysis just like this and receive the rate at which each SG component contributed to total SG. The issue comes when a golfer has negative total SG over an entire tournament.

#### 2020 PGA Championship at Harding Park

| Golfer	      | SG Putt | SG ARG | SG APP | SG OTT | SG Total |
|-----------------|---------|--------|--------|--------|----------|
|Jon Rahm         | -0.10   | 0.84   | 0.44   | 1.10   | 2.28     |

#### 2020 WGC FedEx St. Jude Invitational

| Golfer	      | SG Putt | SG ARG | SG APP | SG OTT | SG Total |
|-----------------|---------|--------|--------|--------|----------|
|Jon Rahm         | 0.09    | -0.61  | -0.64  | 0.47   | -0.70    |

In the case of the PGA Championship above we can divide the -0.10 SG putting by the 2.28 SG total and see that SG putt contributed -4% to Jon's total SG, not a problem. The issue is when total SG is a negative number, when looking at the St. Jude we see that for the tournament Jon was at -0.70 SG (worse than the field numbers in any category doesn't happen often for Rahm, let alone the entire total). When looking for the percent that SG Approach contributed to the total we would divide -0.64/-0.70 and get 91%, not very meaningful. Then we look for the percent of the total that was due to SG around the green and we get -0.61/-0.70 = 87% now we have percentages that add up to greater than 100% and create more confusion than anything that could be remotely useful. To get rid of this issue we take the absolute value of each SG category and add them together to get an absolute total SG value and then divide each original component by that absolute total. I will show how it works with Jon's 2020 St. Jude SG numbers:

#### 2020 WGC FedEx St. Jude Invitational

| Golfer	      | SG Putt | SG ARG | SG APP | SG OTT | SG Total | Absolute Total SG |
|-----------------|---------|--------|--------|--------|----------|-------------------|
|Jon Rahm         | 0.09    | -0.61  | -0.64  | 0.47   | -0.70    | 1.81              |

With absolute total SG we see that the total number of strokes both won and lost to the field was 1.81. We can divide each component SG category by that absolute total to get a better idea of how the poor (negative) categories contributed to SG for the entire tournament:

SG Putting: 4.97%
SG Around the Green: -33.70%
SG Approach: -35.36%
SG OTT: 25.97%

Rather than dealing with percentages that are overly large and positive we now see more reasonable values that show the negative magnitude that SG ARG and SG Approach had on Jon's total strokes gained. We can now use these % of Absolute Total Strokes Gained values to compare components of many player's games across many tournaments and aggregate values in a way that we hope is more meaningful than doing so with raw SG numbers alone. In addition, there will be less variability in % of Absolute Total Strokes Gained when compared to raw SG numbers, this gives us a measure that may be more informative when looking at golfer performance over multiple tournaments.

There are plenty of applications for the percentage of absolute total strokes gained numbers. One of the most logical, as we begin to test the methodology is to compare each SG component to see which is most valuable when it comes to a PGA Tour golfer winning a tournament, finishing in the top 10, and making a cut.

![SG Made Cut vs. Top 10]()

In the visual above, we break strokes gained down into each component and compare golfers that finished in the top 10 of a tournament versus all other golfers who made the cut. We see that putting contributed most to the top 10 golfers distancing themselves from the rest of the field that made it to the weekend. This makes a lot of sense, on any given week the hottest putters over the 4 tournament days usually rise to the top of the field. The top 10 were an average of 25.4 percentage points better in % of Absolute Total Strokes Gained than the rest of the field who made the cut in SG putting. This was followed in importance by SG Approach at an average of +18.6%, then SG Off the Tee at +13.3%, and last was SG Around the Green at +8.6%.

Before we go further let's add in the comparision of golfers that finished 1st in our random selection of 12 tournaments to all other golfers that finished inside the top 10. 

![SG Top 10 vs. 1]()

With fewer data points we have much less tight distributions in this comparison but what does stand out is the role that SG approach plays when it comes to finding a winner out of what we learned previously is probably a group of guys that are putting it really well. On average winners are +11.3% better than the rest of the top 10 in SG Approach. The rest of the top 10 were actually better than the winner in SG around the green (winner -3.6%). Then the difference in SG putting and off the tee between the two groups was negligible, less than 1% in both. 

When taking a look at each of these two group comparisons we see that given that you were a golfer that made the cut it was putting that most likely got you into the top 10 out of the four skills that SG measures. Then out of the golfers in the top 10 it was the best ball strikers that found a way to get the job done and win the tournament. 

The SG data used in the comparison is from a random selection of 12 tournaments from the 2020 PGA Tour season. The tournaments covered include the 3M, BMW, Heritage, Memorial, Northern Trust, PGA Championship, Rocket Mortgage, Charles Schwab, FedEx St. Jude, Travelers, Workday, and Wyndham.

The tournaments feature wins from the following golfers:

- Jon Rahm (2)
- Dustin Johnson (2)
- Collin Morikawa (2)
- Webb Simpson
- Bryson DeChambeau
- Daniel Berger
- Justin Thomas
- Michael Thompson
- Jim Herman

We see some very strong ball strikers in this group, two wins from Collin Morikawa, two wins from Rahm, a win from JT and Berger and you have a group of some of the best iron players in the world. We do feel that we have enough balance though with players like DeChambeau, Thompson, Herman, and even DJ as 2020 winners in the dataset that we can say that we aren't skewed by a group of winners that would typically rely on next level iron play to win a golf tournament.

Other Interesting Notes:

- Brian Harman owns the tournament in the dataset where he relied on the the highest % of SG putting out of Absolute Total Strokes Gained. In the 2020 BMW Championship SG Putting contributed to 83% of his ATSG, he had an average of 1.27 SG putting for the week, 0.03 SG ARG, -0.07 SG Approach, and -0.16 SG OTT. He rode his putter to a T12 finish that week. It ended up being the best SG putting week of the year for Harman, unfortunately he couldn't get any other piece of his game to fire anywhere near as well

- The best average SG putting tournament in the dataset out of anyone that made a cut was a tie between Matt Fitzpatrick and Bryson DeChambeau at the 2020 FedEx St. Jude. Each golfer had an average of 2.5 SG putting on the week, Bryson finished T30, FItzpatrick finished T6.




---------------------------------------------------------------------------------------------------------------------------------
Data from datagolf.com historical SG tournament avergaes