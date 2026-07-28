## Cup: Brickyard 400

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

![Trucks @ North Wilkesboro 2026 | Credit: Patricia McCormack / TheFourthTurn.com](https://github.com/joeah99/Statcar_Images/blob/main/2026_Season/North_Wilkesboro/IMG_9249-1024x683.jpg?raw=true)

### Top 10 Stats Correlated to Finishing Position (2026 North Wilkesboro)



## Trucks: TSport 200



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