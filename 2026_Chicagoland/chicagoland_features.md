## Cup: eero 400

In NASCAR's return to Chicagoland Speedway for the first time since 2019, all of the top 10 most correlated stats to finishing position were team-based. This season there has been a lot more conversation about manufacturers than usual, as since the Daytona 500 there has been a clear divide between the dominating Toyotas, the mediocre Chevrolets, and the struggling Fords. This divide in speed between manufacturers of course carries over to the teams, as Joe Gibbs Racing and 23XI Racing have tended to show the most speed on any given week, followed by Hendrick and then either Penske or Spire it seems.

This past weekend's race at the *new* intermediate track (at least for the NextGen car) was no exception as just like at Nashville, the Joe Gibbs cars swept the podium, and only four teams had a car finish inside the top 13; those being Joe Gibbs Racing of course, Hendrick, 23XI Racing and Penske. The only drivers from those teams to finish outside the top 13 were Kyle Larson (who spun out and fell multiple laps down) and Tyler Reddick (who suffered a punctured oil cooler), and without their respective issues, both drivers almost certainly would have finished inside the top 10.

So with Gibbs, Hendrick, 23XI, and Penske, each with 3+ cars, all grouped together for the most part, and the single-car teams like Hyak, Wood Brothers, and Rick Ware all 'grouped together' by default, it makes sense that team-based overall rating and speed stats dominated the top 10.

**Note:** *Refer to the notes at the bottom of the page for explanations of each stat*

#### Top 10 Stats Correlated to Finishing Position

| rank | feature                              | raw_correlation | abs_correlation |
|:----:|:------------------------------------:|:---------------:|:---------------:|
| 1    | rating_lag1_tracktype_team           | -0.7220881014   | 0.7220881014    |
| 2    | stage_1_position_roll10_general_team | 0.6950921024    | 0.6950921024    |
| 3    | long_team_speed_lag1_tracktype_team  | 0.6928973058    | 0.6928973058    |
| 4    | short_team_speed_lag1_tracktype_team | 0.6909219888    | 0.6909219888    |
| 5    | laps_led_lag1_tracktype_team         | -0.6845756802   | 0.6845756802    |
| 6    | avg_ps_lag1_tracktype_team           | 0.6700714205    | 0.6700714205    |
| 7    | laps_led_roll3_tracktype_team        | -0.6693568984   | 0.6693568984    |
| 8    | BestLapRank_roll30_general_team      | 0.6687545425    | 0.6687545425    |
| 9    | stage_1_position_roll30_general_team | 0.6656818272    | 0.6656818272    |
| 10   | long_team_speed_roll30_general_team  | 0.6637065102    | 0.6637065102    |

## O'Reilly: Cuervo 300

![O'Reilly @ Chicagoland 2026 | Credit: TheFourthTurn.com's Patricia McCormack](https://github.com/joeah99/Statcar_Images/blob/main/2026_Chicagoland/MG_5576-1024x683.jpg?raw=true)

The O'Reilly Auto Parts Series also made its return to Chicagoland this past weekend, but its most important stats for predicting finishing position were driver-based rather than car-or-team-based. The one exception to that was the #1 stat: avg_yellow_pit_crew_roll10_tracktype, or the average caution flag, in-box pit time for each driver over the 10 most recent intermediate track races (which is technically still a driver-based stat, but reflective of their pit crew's performance). Other than that, long term driver stats were the most predictive of finishing position, which makes sense considering there were hardly any upsets in the race. 

The biggest upset in my opinion was the winner, Brandon Jones, but even then, Jones was still predicted to finish top 10 heading into the race and has won a few other intermediate track races before, such as Darlington and Kansas just last year. Other than that, Nick Sanchez in P12 and Garrett Smithley in P18 were the only other notable upsets in my opinion, and there weren't any favorites who had *major* issues other than maybe William Sawalich in P29 and Ryan Sieg in P31, if you for some reason considered either Sawalich or Sieg to be a favorite.

#### Top 10 Stats Correlated to Finishing Position

| rank | feature                              | raw_correlation | abs_correlation |
|:----:|:------------------------------------:|:---------------:|:---------------:|
| 1    | avg_yellow_pit_crew_roll10_tracktype | 0.8446219499    | 0.8446219499    |
| 2    | rating_roll30_general                | -0.8314914104   | 0.8314914104    |
| 3    | avg_ps_roll30_general                | 0.8262391947    | 0.8262391947    |
| 4    | true_points_roll30_general           | -0.8260203523   | 0.8260203523    |
| 5    | is_top_10_roll30_general             | -0.8244692325   | 0.8244692325    |
| 6    | short_team_speed_roll30_general      | 0.8223000328    | 0.8223000328    |
| 7    | mid_ps_roll30_general                | 0.8216884621    | 0.8216884621    |
| 8    | top15_laps_roll30_general            | -0.8111390743   | 0.8111390743    |
| 9    | closing_ps_roll30_general            | 0.8096514757    | 0.8096514757    |
| 10   | top15_laps_roll10_tracktype          | -0.8084920162   | 0.8084920162    |

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




