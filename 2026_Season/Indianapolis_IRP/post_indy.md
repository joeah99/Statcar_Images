## Cup: Brickyard 400

It's shocking to say that it wasn't all that shocking for a part-time driver in his 15th start to win this year's Brickyard 400. Corey Heim is on a never before seen run for a driver in their pre-rookie season. You really have to go as far back as Brad Keselowski in 2009, or better yet Jimmie Johnson in 2002, to see a driver with such little Cup experience perform so well out of the gate. And because of how different the Cup car is from any other series now, and how much we've seen other top prospects like Connor Zilisch struggle in recent years, it's all the more impressive. 

Looking at which stats mattered the most towards predicting the finishing results, team-based stats rose to the top again, as has been the trend recently in the Cup Series. For the most part, general (not track or track-type specific) stats also were most important, with about half being lag1 (the previous race at North Wilkesboro) and half being long-term roll30 stats (average over the past 30 races).

**Note:** *Refer to the notes at the bottom of the page for explanations of each stat*

### Top 10 Stats Correlated to Finishing Position (2026 Indianapolis)

| rank | feature                                | raw_correlation | abs_correlation |
|:----:|:--------------------------------------:|:---------------:|:---------------:|
| 1    | is_top_10_lag1_general_team            | -0.6391198946   | 0.6391198946    |
| 2    | closing_ps_lag1_general_team           | 0.5944048408    | 0.5944048408    |
| 3    | finishing_position_roll30_general_team | 0.5778678228    | 0.5778678228    |
| 4    | starting_position_roll3_track_team     | 0.5647032265    | 0.5647032265    |
| 5    | is_top_25_roll30_general_team          | -0.5631894629   | 0.5631894629    |
| 6    | long_team_speed_lag1_general_team      | 0.5624417763    | 0.5624417763    |
| 7    | avg_ps_lag1_general_team               | 0.5618328534    | 0.5618328534    |
| 8    | is_top_20_roll30_general_team          | -0.5610495032   | 0.5610495032    |
| 9    | true_points_lag1_general_team          | -0.5561682561   | 0.5561682561    |
| 10   | caution_pit_early_roll30_general_team  | 0.5561163967    | 0.5561163967    |


## O'Reilly: Pennzoil 250 presented by Take 5 Oil Change

![O'Reilly @ Indianapolis 2026 | Credit: Logan Riely / Getty Images](https://github.com/joeah99/Statcar_Images/blob/main/2026_Season/Indianapolis_IRP/Carson-Kvapil-and-Sheldon-Creed-Indianapolis-Motor-Speedway-NASCAR-OReilly-Series.webp?raw=true)

The O'Reilly Series race at the Brickyard saw a first-time winner in Carson Kvapil, but a first-time winner that was a long time coming. Really the only unexpected part of the race was seeing Jeremy Clements take the lead early on and win the first stage. 

This year, Clements and his family team have been in alliance with the Haas Factory Team and have been receiving top-of-the-line Hendrick engines, so while that does explain why Clements was able to lead at such an equipment-dependent track like Indianapolis, it certainly does not take away from the fact that he was outpacing all the other Hendrick engine cars: all 5 JR Motorsports cars, both Haas cars, and both (non-start-and-park) RSS Racing cars. Unfortunately for Clements, slow pit stops and late-race mechanical problems kept him out of winning contention.

As for the finishing results themselves, this race was easily one of the most predictable all season, with six individual stats even breaking the 90% correlation threshold. All the most important stats were long rolling averages and tied to carteam (car number + team), indicating that all the fastest cars in recent history performed well and all the slower cars performed poorly. This was pretty much the story of the race, as JJ Yeley in the start-and-park third RSS Racing car was the only DNF and Jeremy Clements was the only driver to have their finishing position severely impacted by something other than car performance. Other than that, Jesse Love and Sammy Smith both struggled quite a bit, but everything else was pretty much spot-on with the trends.

### Top 10 Stats Correlated to Finishing Position (2026 Indianapolis)

| rank | feature                                  | raw_correlation | abs_correlation |
|:----:|:----------------------------------------:|:---------------:|:---------------:|
| 1    | closing_ps_roll30_general_carteam        | 0.9099961714    | 0.9099961714    |
| 2    | stage_2_position_roll30_general_carteam  | 0.9078076284    | 0.9078076284    |
| 3    | starting_position_roll30_general_carteam | 0.9028340081    | 0.9028340081    |
| 4    | top15_laps_roll30_general_carteam        | -0.9019586388   | 0.9019586388    |
| 5    | starting_position_roll10_general_carteam | 0.9015702809    | 0.9015702809    |
| 6    | avg_ps_roll30_general_carteam            | 0.9008644272    | 0.9008644272    |
| 7    | rating_roll30_general_carteam            | -0.8971441077   | 0.8971441077    |
| 8    | mid_ps_roll30_general_carteam            | 0.8958310537    | 0.8958310537    |
| 9    | laps_led_roll30_general_carteam          | -0.8932757765   | 0.8932757765    |
| 10   | true_points_roll30_general_carteam       | -0.8925972547   | 0.8925972547    |

## Trucks: TSport 200

![Trucks @ IRP 2026 | Credit: Patricia McCormack / TheFourthTurn.com](https://github.com/joeah99/Statcar_Images/blob/main/2026_Season/Indianapolis_IRP/IMG_0547-1024x683.jpg?raw=true)

Similar to the Cup Series, team-based stats also dominated the Truck Series race at IRP, and not only that, but they were also split between lag1 (the previous race at North Wilkesboro) and long-term averages. The only exception was starting position, as in the actual starting lineup for the race at IRP, which was just over 76% correlated with the eventual finishing position. Just like last weekend at North Wilkesboro, the Truck race at IRP was pretty predictable overall. Mechanical problems for Christian Eckes and an unfortunate crash taking out Daniel Hemric and Landen Lewis were really the only things that significantly impacted the finishing order relative to expectations.

Regarding the smaller upsets of the race, Connor Mosack arguably ran the best race of his career with a second place finish to Layne Riggs, Gavan Boschele had a seriously impressive debut with an eighth place finish, Michael Christopher Jr and Parker Eatmon both had really solid days, finishing 10th and 12th respectively, and the owner-driver Timmy Hill punched above his weight class with a 19th place finish. 

### Top 10 Stats Correlated to Finishing Position (2026 IRP)

| rank | feature                               | raw_correlation | abs_correlation |
|:----:|:-------------------------------------:|:---------------:|:---------------:|
| 1    | top15_laps_lag1_general_team          | -0.7819981457   | 0.7819981457    |
| 2    | rating_roll30_general_team            | -0.7709606593   | 0.7709606593    |
| 3    | avg_ps_roll30_general_team            | 0.7709606593    | 0.7709606593    |
| 4    | top15_laps_lag1_tracktype_team        | -0.7700961843   | 0.7700961843    |
| 5    | is_top_15_roll30_general_team         | -0.7669553724   | 0.7669553724    |
| 6    | top15_laps_roll10_general_team        | -0.7659243012   | 0.7659243012    |
| 7    | BestLapRank_lag1_general_team         | 0.7657720928    | 0.7657720928    |
| 8    | fast_laps_roll3_general_team          | -0.7644820519   | 0.7644820519    |
| 9    | starting_position                     | 0.7634314476    | 0.7634314476    |
| 10   | starting_position_roll30_general_team | 0.762172279     | 0.762172279     |


#### Explanations of Stats:
- **lag1** = one race prior
- **roll{x}** = average over the past {x} races
- **general** = driver-only data
- **carteam** = car number + team data (ex: 2026 Hendrick 48 carteam data includes all of Alex Bowman, Anthony Alfredo, and Justin Allgaier's stats for their respective races in the Hendrick 48 car)
- **team** = team-only data, taken by averaging the values of each driver on the team in the particular race
- **tracktype** = only data from similar tracks to the current track (ex: short tracks, intermediates, road courses, etc.)
- **track** = only data from the current track
- **rating** = NASCAR's official driver rating score, published in their Loop Data. Refer to [Driver Averages](https://www.driveraverages.com/drvavg/nascar-loopdata.php) for more details on how it is calculated.
- **short_team_speed** = measures short run speed by averaging the driver's top 20% fastest laps in the race
- **long_team_speed** = measures long run speed by averaging the driver's top 80% fastest laps in the race
- **avg_ps** = driver's average running position throughout the race
- **BestLapRank** = driver's rank in practice, based off their fastest lap
- **OverAllAvgRank** = driver's rank in practice, based off their average lap
- **true_points** = the points system used in the official NASCAR Fantasy Live game (the same as the normal points system, except giving points to series-ineligible drivers)
- **is_top_{x}** = finished in the top {x} in the race
- **mid_ps** = driver's running position at the halfway point in the race
- **top15_laps** = number of laps the driver spent running inside the top 15 in the race
- **closing_ps** = driver's running position with 10% of the race left to go
- **avg_yellow_pit_crew** = driver's average time in the pit box during caution flag stops over the course of the race
- **avg_green_pit_crew** = driver's average time in the pit box during green flag stops over the course of the race
- **avg_yellow_pit_driver** = driver's average time on and off pit road (excluding the time spent in the pit box) during caution flag stops over the course of the race
- **avg_green_pit_driver** = driver's average time on and off pit road (excluding the time spent in the pit box) during green flag stops over the course of the race
- **caution_pit_early** = tail end penalty for pitting before pit road is open under caution (usually to repair damage, so not indicative of a pit road mistake)
- **num_long_stops** = number of pit stops longer than 25 seconds for Cup, and longer than 30 seconds for O'Reilly and Trucks
- **quality_passes** = number of green flag passes a driver makes while running inside the top 15
- **diff_laps** = number of laps down a driver finishes to the winner
- **best_lap_speed** = driver's fastest lap speed in the race
- **fast_laps** = number of laps in which the driver records a faster time than anyone else that lap