## Cup: Brickyard 400

From 2021 to 2023, NASCAR retired the iconic Brickyard 400 on the Indianapolis oval in favor of the track's grand prix road course layout. But in 2024, the oval was brought back and has put on some great racing in the Next Gen car; much better than the Gen-6 racing product that likely convinced NASCAR to take the race off the schedule. But both Next Gen Brickyard 400s so far have been quite chaotic towards the end, and both have resulted in multiple overtime attempts. 

Nevertheless, multiple medium-to-long-term, team-based speed-and-consistency stats were pretty important in predicting last year's Brickyard 400 finishing results. The top 4 stats, all more than 56% correlated with eventual finishing position, include: 
- team-average number of caution pit early penalties over the past 10 races (usually these penalties are for damaged cars pitting before pit road is open, and thus a low number of these penalties signals good crash avoidance)
- team-average number of laps spent inside the top 15 over the past 30 races
- team-average fastest practice lap rank over the past 30 races
- team-average running position at the halfway point of the race, over the past 10 big intermediate track races

Looking at all big intermediate tracks (Michigan, Pocono, & Indianapolis) last year and so far this year, no individual stat broke 50% correlation with finishing position, but clearly raw speed in past races (seen by number of fastest laps), and practice speed during the race weekend, has been the best indicator of eventual finishing position. 

**Note:** *Refer to the notes at the bottom of the page for explanations of each stat*

### Top 10 Stats Correlated to Finishing Position (2025 Indianapolis)

| rank | feature                               | raw_correlation | abs_correlation |
|:----:|:-------------------------------------:|:---------------:|:---------------:|
| 1    | caution_pit_early_roll10_general_team | 0.6094793194    | 0.6094793194    |
| 2    | top15_laps_roll30_general_team        | -0.6046558704   | 0.6046558704    |
| 3    | BestLapRank_roll30_general_team       | 0.5618989805    | 0.5618989805    |
| 4    | mid_ps_roll10_tracktype_team          | 0.5616965309    | 0.5616965309    |
| 5    | top15_laps_roll10_tracktype_team      | -0.5591093117   | 0.5591093117    |
| 6    | is_top_10_lag1_tracktype_carteam      | -0.558281977    | 0.558281977     |
| 7    | is_top_10_lag1_tracktype              | -0.558281977    | 0.558281977     |
| 8    | is_top_10_lag1_general                | -0.558281977    | 0.558281977     |
| 9    | is_top_10_lag1_general_carteam        | -0.558281977    | 0.558281977     |
| 10   | fast_laps_roll10_tracktype_team       | -0.5497042213   | 0.5497042213    |

### Top 10 Stats Correlated to Finishing Position (All Big Intermediates in 2025 & 2026)

| rank | feature                            | raw_correlation | abs_correlation |
|:----:|:----------------------------------:|:---------------:|:---------------:|
| 1    | fast_laps_roll10_tracktype_carteam | -0.4613714094   | 0.4613714094    |
| 2    | fast_laps_roll10_tracktype         | -0.4471415088   | 0.4471415088    |
| 3    | fast_laps_lag1_tracktype           | -0.4429588126   | 0.4429588126    |
| 4    | BestLapRank_roll10_general         | 0.4355665838    | 0.4355665838    |
| 5    | BestLapRank_roll10_general_carteam | 0.4303902872    | 0.4303902872    |
| 6    | laps_led_roll10_tracktype_carteam  | -0.4283356963   | 0.4283356963    |
| 7    | rating_roll10_tracktype_carteam    | -0.4275058629   | 0.4275058629    |
| 8    | BestLapRank_roll10_general_team    | 0.4246778505    | 0.4246778505    |
| 9    | avg_green_pit_crew_roll30_general  | 0.4218600007    | 0.4218600007    |
| 10   | fast_laps_lag1_tracktype_carteam   | -0.4207895314   | 0.4207895314    |


## O'Reilly: Pennzoil 250

![O'Reilly @ Indianapolis 2025 | Credit: Jonathan Bachman / Getty Images](https://github.com/joeah99/Statcar_Images/blob/main/2026_Season/Indianapolis_IRP/larson-allgaier-mayer-jones-race-action-pennzoil-250-indianapolis-2025.jpg?raw=true)

Since NASCAR's 2024 return to the Indy oval, both O'Reilly races have arguably put on even better racing than the Cup Series, and while the O'Reilly Series races have been a bit more chaotic overall, neither race has gone past its scheduled distance.

In last year's Indy race, carteam (car number + team combination) finishing position from Pocono (the most recent big intermediate oval race) was the best indicator of finishing position, followed by average carteam long run speed (top 80% of the carteam's lap times from the race) over the past 10 big intermediate races, and then simply whether the carteam finished inside the top 25 at Pocono. So if these stats are anything to go off for this year's race, pay attention to this year's Pocono results and race data as well as carteam speed ratings from the past few big intermediate track races.

Combining the big intermediate ovals from two years ago, last year and so far this year (NASCAR took Michigan off the O'Reilly schedule in 2025 so I wanted to get a bigger sample size of races), general carteam speed and running position stats took over (meaning stats independent of track or track-type)

### Top 10 Stats Correlated to Finishing Position (2025 Indianapolis)

| rank | feature                                      | raw_correlation | abs_correlation |
|:----:|:--------------------------------------------:|:---------------:|:---------------:|
| 1    | finishing_position_lag1_tracktype_carteam    | 0.5657383605    | 0.5657383605    |
| 2    | long_team_speed_roll10_tracktype_carteam     | 0.5439325966    | 0.5439325966    |
| 3    | is_top_25_lag1_tracktype_carteam             | -0.5348231386   | 0.5348231386    |
| 4    | avg_yellow_pit_driver_roll30_general_carteam | 0.5279571069    | 0.5279571069    |
| 5    | closing_ps_lag1_tracktype_carteam            | 0.5262063683    | 0.5262063683    |
| 6    | restart_surge_lag1_general                   | -0.5195037694   | 0.5195037694    |
| 7    | true_points_lag1_tracktype_carteam           | -0.5176226199   | 0.5176226199    |
| 8    | avg_ps_lag1_tracktype_carteam                | 0.5167149978    | 0.5167149978    |
| 9    | best_lap_speed_lag1_tracktype_carteam        | -0.5146077251   | 0.5146077251    |
| 10   | rating_lag1_tracktype_carteam                | -0.5139511982   | 0.5139511982    |


### Top 10 Stats Correlated to Finishing Position (All Big Intermediates in 2024, 2025 & 2026)

| rank | feature                                 | raw_correlation | abs_correlation |
|:----:|:---------------------------------------:|:---------------:|:---------------:|
| 1    | stage_1_position_roll10_general_carteam | 0.539957701     | 0.539957701     |
| 2    | best_lap_speed_roll10_general_carteam   | -0.5304566728   | 0.5304566728    |
| 3    | stage_1_position_roll30_general_carteam | 0.5299005722    | 0.5299005722    |
| 4    | avg_ps_roll30_general_carteam           | 0.5219855396    | 0.5219855396    |
| 5    | closing_ps_roll30_general               | 0.5186715788    | 0.5186715788    |
| 6    | mid_ps_roll30_general_carteam           | 0.5185919989    | 0.5185919989    |
| 7    | avg_ps_roll10_general_carteam           | 0.5182676468    | 0.5182676468    |
| 8    | stage_2_position_roll30_general_carteam | 0.5160129112    | 0.5160129112    |
| 9    | is_top_15_roll30_general                | -0.5156904355   | 0.5156904355    |
| 10   | stage_2_position_roll10_general_carteam | 0.514894726     | 0.514894726     |


## Trucks: TSport 200

![Trucks @ Lucas Oil IRP 2025 | Credit: McAnally-Hilgemann Racing](https://github.com/joeah99/Statcar_Images/blob/main/2026_Season/Indianapolis_IRP/DBP_25IRP1_250725_NW24291.jpg?raw=true)

Lastly for the Truck Series race, which as usual will be held at the Indianapolis Raceway Park (IRP) short track (as opposed to the big oval), carteam running position and raw speed stats over the past 10 races in general were very important in predicting last year's IRP results, and the same can be said about all recent Truck Series short track races. 

While the Truck Series races on superspeedways, intermediates, road courses, and even Bristol, have been especially chaotic this season, our Statcar projected results model achieved a season-best finishing position correlation of 0.725 last week at North Wilkesboro, and given how similar North Wilkesboro is to IRP, and IRP's high predictability last year, I would say the race at IRP this coming weekend will once again be much easier to predict than the average Truck Series race.

### Top 10 Stats Correlated to Finishing Position (2025 Lucas Oil IRP)

| rank | feature                                      | raw_correlation | abs_correlation |
|:----:|:--------------------------------------------:|:---------------:|:---------------:|
| 1    | stage_2_position_roll10_general_carteam      | 0.8532406598    | 0.8532406598    |
| 2    | stage_1_position_roll10_general_carteam      | 0.8402298901    | 0.8402298901    |
| 3    | mid_ps_roll10_general_carteam                | 0.8389357728    | 0.8389357728    |
| 4    | short_team_speed_roll10_general_carteam      | 0.8338806837    | 0.8338806837    |
| 5    | best_lap_speed_roll10_general_carteam        | -0.825670503    | 0.825670503     |
| 6    | average_restart_speed_roll10_general_carteam | -0.8220580235   | 0.8220580235    |
| 7    | avg_ps_roll10_general_carteam                | 0.8206349256    | 0.8206349256    |
| 8    | BestLapRank_roll3_general_carteam            | 0.8197000348    | 0.8197000348    |
| 9    | finishing_position_roll10_general_carteam    | 0.8135983225    | 0.8135983225    |
| 10   | BestLapTime_roll10_general_team              | 0.8079382101    | 0.8079382101    |


### Top 10 Stats Correlated to Finishing Position (All Short Tracks in 2025 & 2026)

| rank | feature                                   | raw_correlation | abs_correlation |
|:----:|:-----------------------------------------:|:---------------:|:---------------:|
| 1    | rating_roll10_general_carteam             | -0.6792160655   | 0.6792160655    |
| 2    | avg_ps_roll10_general_carteam             | 0.6774951518    | 0.6774951518    |
| 3    | closing_ps_roll10_general_carteam         | 0.6628865502    | 0.6628865502    |
| 4    | rating_roll10_general                     | -0.6611351762   | 0.6611351762    |
| 5    | true_points_roll10_general_carteam        | -0.6603076231   | 0.6603076231    |
| 6    | finishing_position_roll10_general_carteam | 0.6599005535    | 0.6599005535    |
| 7    | short_team_speed_roll10_general_carteam   | 0.6596779402    | 0.6596779402    |
| 8    | rating_roll30_general_carteam             | -0.6578217438   | 0.6578217438    |
| 9    | avg_ps_roll30_general_carteam             | 0.6574581994    | 0.6574581994    |
| 10   | rating_roll30_general                     | -0.6561083726   | 0.6561083726    |


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