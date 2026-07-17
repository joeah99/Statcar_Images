## Cup: Window World 450

The NASCAR Cup Series returned to North Wilkesboro Speedway in 2023 to make it the temporary home of the All Star Race, but this weekend, the Cup Series returns for the first time since 1996 for a points-paying event. It should definitely be an exciting race, but from a prediction perspective, it could be rather difficult. We have three year's worth of All Star Race and All Star Open data to work with, but those races each consisted of roughly half the laps and half the number of cars that will be seen this weekend. Additionally, those "half races" were (for the most part) split in skill level, as the All Star Races only included recent winners, past All Star Race winners, and the top two finishers from the Open...and the fan vote winner, which happened to be Noah Gragson all three years that the All Star Race was at North Wilkesboro. 

To attempt to still make use of the All Star Race data, I sort of zombified the All Star and Open results into one race, with the best finishing Open driver who didn't advance into the All Star Race getting credited as finishing one spot worse than the last place All Star Race finisher. So, the Track points you will see on the Fantasy Helper page this week are based off the points from these zombified races, in which I also listed everyone as receiving zero stage points. 

That said, be warned that Noah Gragson, who "artificially" advanced into the All Star Race for the past three years has a lot better track-specific data than he probably should, and also the worst-performing All Star Race drivers are probably wrongfully ranked ahead of the best-performing Open drivers who didn't make it into the All-Star race. Regardless, I think this zombifying method is the best for making use of the recent All Star Races at North Wilkesboro, and especially better than having no track data at all.

Now as for the most correlated stats to finishing position in last year's All Star Race at North Wilkesboro (the actual All Star Race, not my zombified version), general long-term finishing position and consistency stats were at the top of the board.

And as for all short track races combined from 2025 and so far in 2026, more general speed and consistency stats rose to the top, as well as short-track-specific short run and long run speed. On the short tracks like North Wilkesboro, both short run and long run speed / tire saving are about equally as important due to the high frequency of late race cautions, and the all-but-guaranteed 100+ lap green flag runs in the middle of the race.

**Note:** *Refer to the notes at the bottom of the page for explanations of each stat*

### Top 10 Stats Correlated to Finishing Position (2025 All Star Race at North Wilkesboro)

| rank | feature                                   | raw_correlation | abs_correlation |
|:----:|:-----------------------------------------:|:---------------:|:---------------:|
| 1    | closing_ps_roll10_general                 | 0.6818181818    | 0.6818181818    |
| 2    | closing_ps_roll10_general_carteam         | 0.6798418972    | 0.6798418972    |
| 3    | is_top_20_roll10_general                  | -0.6482107027   | 0.6482107027    |
| 4    | is_top_20_roll10_general_carteam          | -0.647046589    | 0.647046589     |
| 5    | mid_ps_roll30_general_carteam             | 0.6434396045    | 0.6434396045    |
| 6    | is_top_15_roll10_general                  | -0.6397524197   | 0.6397524197    |
| 7    | is_top_15_roll10_general_carteam          | -0.6397524197   | 0.6397524197    |
| 8    | finishing_position_roll10_general         | 0.6228374463    | 0.6228374463    |
| 9    | finishing_position_roll10_general_carteam | 0.6208601846    | 0.6208601846    |
| 10   | avg_ps_roll30_general_carteam             | 0.6106719368    | 0.6106719368    |

### Top 10 Stats Correlated to Finishing Position (All Short Track Races in 2025 & 2026)

| rank | feature                                  | raw_correlation | abs_correlation |
|:----:|:----------------------------------------:|:---------------:|:---------------:|
| 1    | rating_roll30_general_carteam            | -0.5345637291   | 0.5345637291    |
| 2    | top15_laps_roll30_general_carteam        | -0.5331825101   | 0.5331825101    |
| 3    | top15_laps_roll30_general                | -0.5243779751   | 0.5243779751    |
| 4    | avg_ps_roll30_general_carteam            | 0.5242385829    | 0.5242385829    |
| 5    | rating_roll30_general                    | -0.5237726853   | 0.5237726853    |
| 6    | avg_ps_roll30_general                    | 0.5169105537    | 0.5169105537    |
| 7    | long_team_speed_roll10_tracktype         | 0.5143295943    | 0.5143295943    |
| 8    | starting_position_roll30_general_carteam | 0.5137202603    | 0.5137202603    |
| 9    | short_team_speed_roll10_tracktype        | 0.5115581791    | 0.5115581791    |
| 10   | avg_ps_roll10_tracktype                  | 0.5108801457    | 0.5108801457    |

## Trucks: FaithFest 250

![Trucks @ North Wilkesboro 2025 | Credit: James Gilbert / Getty Images](https://github.com/joeah99/Statcar_Images/blob/main/2026_Season/North_Wilkesboro/Trucks%202025%20NW.jpg?raw=true)

Unlike the Cup Series, the predictions for this weekend's Truck Series race are much more straight forward, as since their return to North Wilkesboro in 2023, the Truck Series has ran standard points-paying races at the track each year. 

Last year's race at North Wilkesboro in particular was very predictable, with multiple general speed and average running position stats correlating just shy of 90% with finishing position. Not a single truck failed to finish the race due to a crash, and there were only 4 mechanical failure DNFs (all from low-budget teams). Really the only wild factor in the finishing order at all was Corey Heim falling to 17th place, after leading 162 laps, but then spinning out on the final lap in an intense overtime battle with Layne Riggs and Chandler Smith. All three of those drivers will be back in the field this weekend, and will certainly be among the favorites once again.

As for all the short track races last year and so far this year combined, there is a lot less certainty, but still a strong correlation between relatively recent and long-term general speed and average running position stats, and actual finishing position.

### Top 10 Stats Correlated to Finishing Position (2025 North Wilkesboro)

| rank | feature                                 | raw_correlation | abs_correlation |
|:----:|:---------------------------------------:|:---------------:|:---------------:|
| 1    | short_team_speed_roll10_general         | 0.8939648587    | 0.8939648587    |
| 2    | short_team_speed_roll10_general_carteam | 0.8847975554    | 0.8847975554    |
| 3    | avg_ps_roll30_general_carteam           | 0.882658518     | 0.882658518     |
| 4    | rating_roll30_general_carteam           | -0.8789915966   | 0.8789915966    |
| 5    | best_lap_speed_roll10_tracktype_carteam | -0.8774637128   | 0.8774637128    |
| 6    | rating_roll10_general_carteam           | -0.8762414057   | 0.8762414057    |
| 7    | avg_ps_roll10_general_carteam           | 0.8750190985    | 0.8750190985    |
| 8    | true_points_roll30_general_carteam      | -0.8728800611   | 0.8728800611    |
| 9    | top15_laps_roll30_general_carteam       | -0.8728800611   | 0.8728800611    |
| 10   | best_lap_speed_roll30_general_carteam   | -0.8713521772   | 0.8713521772    |

### Top 10 Stats Correlated to Finishing Position (All Short Track Races in 2025 & 2026)

| rank | feature                                 | raw_correlation | abs_correlation |
|:----:|:---------------------------------------:|:---------------:|:---------------:|
| 1    | rating_roll10_general_carteam           | -0.6739107672   | 0.6739107672    |
| 2    | avg_ps_roll10_general_carteam           | 0.6661052173    | 0.6661052173    |
| 3    | rating_roll10_general                   | -0.6631746835   | 0.6631746835    |
| 4    | rating_roll30_general                   | -0.6613791507   | 0.6613791507    |
| 5    | rating_roll30_general_carteam           | -0.6596996934   | 0.6596996934    |
| 6    | mid_ps_roll10_general_carteam           | 0.6556534739    | 0.6556534739    |
| 7    | true_points_roll10_general_carteam      | -0.6556260122   | 0.6556260122    |
| 8    | avg_ps_roll30_general_carteam           | 0.6550619997    | 0.6550619997    |
| 9    | closing_ps_roll10_general_carteam       | 0.6526539879    | 0.6526539879    |
| 10   | short_team_speed_roll10_general_carteam | 0.6516359894    | 0.6516359894    |

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