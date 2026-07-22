## Cup: Window World 450

Although the Cup Series equipment gap has shrunk overall with the introduction of the NextGen car in 2022 and its many standardized parts, Sunday's race at North Wilkesboro would have you thinking otherwise. In the most recent points-paying race at North Wilkesboro in 1996, eleven cars finished on the lead lap, but this past Sunday, only six cars did.

After 450 laps on any short track, you can expect to see fewer cars on the lead lap than not (unless there are a high number of cautions), but two factors in particular contributed to the *very* low number of cars on the lead lap. First, an untimely caution in the middle of stage 2 green flag pit stops trapped multiple top 10 drivers not just one, but two laps down. And second, Joey Logano was flat out dominant. His only real competition in the final stage, Denny Hamlin, trailed closely behind, but everyone else was outside of his ballpark.

But despite the green flag pit stop incident shuffling up the running order and multiple upsets in the top 10, especially SVG finishing 5th and Todd Gilliland finishing 8th, there were still pretty strong correlations between some individual stats and finishing position.

As has been the trend in the Cup Series recently, team-level stats, particularly long-term ones, were the most predictive of finishing position. Of note, three of the top four stats had to do with average restart speed over the past 10 short track races. Given the long green flag runs in the race, including a completely green final stage, restart speed likely didn't play much of a role in the finishing results, but at the same time, getting track position at a harder-to-pass track like North Wilkesboro is extremely important, and naturally a lot of the best short track restarters are also just good short track racers in general. Note that it is also much easier to take off fast on a restart if you are already at the front of the pack.

**Note:** *Refer to the notes at the bottom of the page for explanations of each stat*

### Top 10 Stats Correlated to Finishing Position (2026 North Wilkesboro)

| rank | feature                                        | raw_correlation | abs_correlation |
|:----:|:----------------------------------------------:|:---------------:|:---------------:|
| 1    | average_restart_speed_roll10_tracktype_team    | -0.7081156901   | 0.7081156901    |
| 2    | average_restart_speed_roll10_tracktype_carteam | -0.6901375059   | 0.6901375059    |
| 3    | is_top_10_lag1_tracktype_team                  | -0.6885525456   | 0.6885525456    |
| 4    | average_restart_speed_roll10_tracktype         | -0.6880037933   | 0.6880037933    |
| 5    | is_top_15_roll30_general_team                  | -0.6866527706   | 0.6866527706    |
| 6    | is_top_20_roll30_general_team                  | -0.6841852716   | 0.6841852716    |
| 7    | finishing_position_roll30_general_team         | 0.6719788477    | 0.6719788477    |
| 8    | quality_passes_roll10_tracktype_team           | -0.6610426981   | 0.6610426981    |
| 9    | is_top_25_roll30_general_team                  | -0.6586965255   | 0.6586965255    |
| 10   | avg_ps_roll10_tracktype_team                   | 0.6572388199    | 0.6572388199    |

## Trucks: FaithFest 250

![Trucks @ North Wilkesboro 2026 | Credit: Patricia McCormack / TheFourthTurn.com](https://github.com/joeah99/Statcar_Images/blob/main/2026_Season/North_Wilkesboro/IMG_9249-1024x683.jpg?raw=true)

The Truck race at North Wilkesboro was the cleanest all season, and was definitely a breath of fresh air after the series' especially chaotic two most recent races. Like the Cup race, the final stage went completely green, and there were also quite a few upsets in the top 10. While it wouldn't have been that much of a longshot to predict SVG finishing top 10, I don't think anyone had him in third place behind the wheel of the part-time #71 Spire truck. The same can be said for series' newest road course ace Landen Lewis, who earned his first oval top 5 finish. And while not quite in the top 10, Lewis's teammate Tyler Reif also performed better than most thought he would with a 12th place finish. After this race, I would definitely expect Lewis to get bumped up to full-time status next year, but I need to see a bit more from Reif to say the same about him.

On the flip side, my pick to win, Corey Heim, finally showed weakness in the Truck Series, finishing back in ninth place and losing his record-smashing 31 straight race streak of leading at least one lap. This was Heim's sixth Truck start of 2026 and his second in the TRICON #5 truck. In his first and only time driving the #5, he won at Darlington with an incredible final lap pass on Ross Chastain, but the #5 has always been the weak link of TRICON's Truck operation and that was definitely on display this past weekend.

The winning pick for many of the sports betting apps was Christopher Bell, the 2025 All Star Race winner at North Wilkesboro and the most recent Truck Series winner on a short track, but he too struggled in the race, falling back to finish in 15th place, one lap down.

But while two of the top picks struggled, multiple individual stats still had very strong correlations to finishing position, simply by nature of the race running green for so long. This time around, most of the top correlated stats were speed-or-consistency-related stats over the 10 most recent races in general. Most were also related to carteam (the truck number + team combination), which is to be expected in the Truck Series, where there are typically many part-time drivers switching in and out of full-time trucks.

### Top 10 Stats Correlated to Finishing Position (2026 North Wilkesboro)

| rank | feature                                   | raw_correlation | abs_correlation |
|:----:|:-----------------------------------------:|:---------------:|:---------------:|
| 1    | top15_laps_roll10_general_carteam         | -0.803479593    | 0.803479593     |
| 2    | finishing_position_roll10_general         | 0.7748960432    | 0.7748960432    |
| 3    | starting_position_roll10_general_carteam  | 0.7677828893    | 0.7677828893    |
| 4    | fast_laps_roll30_general_carteam          | -0.764413005    | 0.764413005     |
| 5    | stage_1_position_roll10_general_carteam   | 0.7618995514    | 0.7618995514    |
| 6    | closing_ps_roll10_general_carteam         | 0.7606697353    | 0.7606697353    |
| 7    | avg_ps_roll10_general_carteam             | 0.7597111281    | 0.7597111281    |
| 8    | finishing_position_roll10_general_carteam | 0.7542544561    | 0.7542544561    |
| 9    | rating_roll10_general_carteam             | -0.75424007     | 0.75424007      |
| 10   | is_top_10_roll10_general                  | -0.754229155    | 0.754229155     |

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