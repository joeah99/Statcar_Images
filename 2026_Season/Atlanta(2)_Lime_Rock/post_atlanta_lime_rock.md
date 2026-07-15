## Cup: Quaker State 400

Strangely enough, the Cup Series race at EchoPark / Atlanta was easily the most predictable NASCAR race of the weekend. In last year's summer Atlanta race, only 21 cars finished on the lead lap, and only about 15 finished without significant damage, but this time 29 cars finished on the lead lap, and almost all of them were without significant damage.

Statcar's winning, top 3, top 5, and top 10 odds performed exceptionally well, correctly predicting Ryan Blaney as the winner and beating out DraftKings, FanDuel, and BetMGM's de-vigged odds in multiple categories. Statcar's projected results ranking model also outperformed NASCAR's Racing Insights (Spearman of 0.551 vs. 0.528) after back to back losses to Racing Insights at Sonoma and Chicagoland.

As for which features turned out to be the most important in predicting the finishing order this week, long term mechanical failure rate and quality passes jumped to the top, and driver rating lag1 tracktype (NASCAR Loop Data driver rating from the most recent superspeedway race) was also highly correlated.

While quality passes and driver rating make sense, I was pretty confused why a stat like long term mechanical failures was so important, especially for a race that was relatively clean. In a total wreckfest like last year's summer Atlanta race, you can expect to see weird stats appear at the top of the list since essentially no individual stats were meaningfully correlated to finishing position, but for a relatively clean race, you would expect mostly speed-and-consistency based stats to be at the top.

So expectedly, after doing some digging, it turned out that the mechanical failure correlation was *mostly* a coincidence:

**The Signal**: The two non-chartered entries of Chad Finchum and BJ McLeod (both part-time drivers with part-time teams, so their and their teams' past 30 races span over multiple years) have each had their share of mechanical failures over the past few seasons, and also predictably finished pretty poorly in the race (and funny enough McLeod suffered a mechanical failure). 

**The Noise**: Over the recent decades, mechanical failure rates among NASCAR's full-time teams have decreased dramatically (so far in 2026 there have only been 9 total mechanical failures from full-time teams). But coincidentally, many of the full-time teams who have had fluke mechanical failures in the past 30 races also had bad results this past weekend. Specifically, Cody Ware, AJ Allmendinger, Josh Berry, Brad Keselowski, Riley Herbst, Chase Briscoe, Bubba Wallace, Connor Zilisch, Noah Gragson, and Zane Smith have all had at least one mechanical failure in their past 30 races, and all of them finished 25th or worse this past weekend.

**Note:** *Refer to the notes at the bottom of the page for explanations of each stat*

### Top 10 Stats Correlated to Finishing Position (2026 Summer Atlanta)

| rank | feature                                   | raw_correlation | abs_correlation |
|:----:|:-----------------------------------------:|:---------------:|:---------------:|
| 1    | mechanical_failure_roll30_general         | 0.6653343735    | 0.6653343735    |
| 2    | mechanical_failure_roll30_general_carteam | 0.6567547558    | 0.6567547558    |
| 3    | quality_passes_roll10_general_carteam     | -0.6084149487   | 0.6084149487    |
| 4    | quality_passes_roll10_general             | -0.5766031989   | 0.5766031989    |
| 5    | rating_lag1_tracktype_carteam             | -0.5706313601   | 0.5706313601    |
| 6    | rating_lag1_tracktype                     | -0.5649414597   | 0.5649414597    |
| 7    | quality_passes_lag1_tracktype_carteam     | -0.5538529195   | 0.5538529195    |
| 8    | is_top_25_roll30_general                  | -0.5496073294   | 0.5496073294    |
| 9    | is_top_25_roll30_general_carteam          | -0.5493005027   | 0.5493005027    |
| 10   | closing_ps_roll30_general_carteam         | 0.5431963678    | 0.5431963678    |

### Here are all the mechanical failures in the past 30 Cup races for those interested:

| Year | Track Name                           | Car # | Driver Name        | Team Name             | Laps Completed | Mech Failure |
|:----:|:------------------------------------:|:-----:|:------------------:|:---------------------:|:--------------:|:------------:|
| 2025 | Daytona International Speedway       | 77    | Carson Hocevar     | Spire Motorsports     | 81             | Engine       |
| 2025 | Darlington Raceway                   | 44    | Derek Kraus        | NY Racing Team        | 282            | Mechanical   |
| 2025 | Darlington Raceway                   | 51    | Cody Ware          | Rick Ware Racing      | 249            | Suspension   |
| 2025 | Bristol Motor Speedway               | 66    | Chad Finchum       | Garage 66             | 458            | Brakes       |
| 2025 | Bristol Motor Speedway               | 16    | AJ Allmendinger    | Kaulig Racing         | 408            | Steering     |
| 2025 | Bristol Motor Speedway               | 21    | Josh Berry         | Wood Brothers Racing  | 75             | Brakes       |
| 2025 | Charlotte Motor Speedway Road Course | 6     | Brad Keselowski    | RFK Racing            | 89             | Drivetrain   |
| 2025 | Talladega Superspeedway              | 51    | Cody Ware          | Rick Ware Racing      | 165            | Engine       |
| 2025 | Talladega Superspeedway              | 35    | Riley Herbst       | 23XI Racing           | 141            | Engine       |
| 2025 | Talladega Superspeedway              | 21    | Josh Berry         | Wood Brothers Racing  | 133            | Drivetrain   |
| 2025 | Martinsville Speedway                | 66    | Casey Mears        | Garage 66             | 478            | Electrical   |
| 2025 | Martinsville Speedway                | 11    | Denny Hamlin       | Joe Gibbs Racing      | 334            | Engine       |
| 2025 | Martinsville Speedway                | 35    | Riley Herbst       | 23XI Racing           | 323            | Engine       |
| 2025 | Martinsville Speedway                | 19    | Chase Briscoe      | Joe Gibbs Racing      | 295            | Engine       |
| 2025 | Phoenix Raceway                      | 23    | Bubba Wallace      | 23XI Racing           | 165            | Brakes       |
| 2026 | Circuit of The Americas              | 19    | Chase Briscoe      | Joe Gibbs Racing      | 62             | Transaxle    |
| 2026 | Phoenix Raceway                      | 88    | Connor Zilisch     | Trackhouse Racing     | 281            | Suspension   |
| 2026 | Phoenix Raceway                      | 41    | Cole Custer        | Haas Factory Team     | 159            | Radiator     |
| 2026 | Martinsville Speedway                | 10    | Ty Dillon          | Kaulig Racing         | 298            | Brakes       |
| 2026 | Darlington Raceway                   | 66    | Timmy Hill         | Garage 66             | 52             | Handling     |
| 2026 | Bristol Motor Speedway               | 66    | Chad Finchum       | Garage 66             | 241            | Steering     |
| 2026 | Charlotte Motor Speedway             | 66    | Timmy Hill         | Garage 66             | 291            | Fire         |
| 2026 | Nashville Superspeedway              | 60    | Ryan Preece        | RFK Racing            | 90             | Radiator     |
| 2026 | Pocono Raceway                       | 4     | Noah Gragson       | Front Row Motorsports | 107            | Handling     |
| 2026 | Pocono Raceway                       | 38    | Zane Smith         | Front Row Motorsports | 66             | Handling     |
| 2026 | San Diego Street Course              | 47    | Ricky Stenhouse Jr | HYAK Motorsports      | 59             | Radiator     |
| 2026 | San Diego Street Course              | 20    | Christopher Bell   | Joe Gibbs Racing      | 28             | Engine       |
| 2026 | Atlanta Motor Speedway               | 78    | BJ McLeod          | Live Fast Motorsports | 105            | Mechanical   |

## O'Reilly: Focused Health 250

![O'Reilly @ Atlanta (2) 2026 | Credit: NASCAR.com](https://github.com/joeah99/Statcar_Images/blob/main/2026_Season/Atlanta(2)_Lime_Rock/OReilly%20Atlanta%20Allgaier.jpg?raw=true)

In a much more chaotic O'Reilly Series race at Atlanta, various pit penalty stats and crash-rate stats dominated the top 10, specifically from the most recent race in general (Chicagoland) and the most recent superspeedway race (Talladega). 

This year's spring Talladega race was actually pretty clean as only three drivers failed to finish due to a crash: Sam Mayer, Jeb Burton, and Harrison Burton, and all of them had a pretty rough time out this past weekend as well, which explains the correlation there.

As for the (inverse) penalty trend, I provided a table below showing drivers who received penalties either at Chicagoland or Talladega and how they finished at Atlanta. This correlation is arguably an even bigger coincidence than the mechanical failure correlation from the Cup race. Note that the top 6 most-penalty-earning carteams at Talladega and Chicagoland (RSS 39, BMR 48, DGM 91, JRM 7, JGR 18, RSS 28), who accounted for 25 of the 47 total pit penalties across both races, all finished 16th or better this past weekend.

### Top 10 Stats Correlated to Finishing Position (2026 Summer Atlanta)

| rank | feature                                       | raw_correlation | abs_correlation |
|:----:|:---------------------------------------------:|:---------------:|:---------------:|
| 1    | caution_pit_early_lag1_general_carteam        | -0.5141638313   | 0.5141638313    |
| 2    | green_pit_penalty_lag1_tracktype              | -0.4848190685   | 0.4848190685    |
| 3    | green_pit_penalty_lag1_tracktype_carteam      | -0.4848190685   | 0.4848190685    |
| 4    | true_caution_pit_penalty_lag1_general_carteam | -0.4339891927   | 0.4339891927    |
| 5    | crash_out_lag1_tracktype_carteam              | 0.4300814317    | 0.4300814317    |
| 6    | crash_out_lag1_tracktype                      | 0.4300814317    | 0.4300814317    |
| 7    | closing_laps_diff_lag1_tracktype_team         | -0.4297733716   | 0.4297733716    |
| 8    | diff_laps_roll10_general_carteam              | 0.4249891744    | 0.4249891744    |
| 9    | caution_pit_early_roll3_general_carteam       | -0.4170130244   | 0.4170130244    |
| 10   | crash_out_roll10_general_carteam              | 0.4109494568    | 0.4109494568    |

**Note:** # of Penalties = total number of pit penalties received at Talladega and Chicagoland combined

| Car Number | Team Name              | Driver Name(s)                 | # of Pit Penalties | Atlanta Finish (Carteam) |
|:----------:|:----------------------:|:------------------------------:|:------------------:|:------------------------:|
| 39         | RSS Racing             | Ryan Sieg                      | 5                  | 16                       |
| 48         | Big Machine Racing     | Patrick Staropoli              | 5                  | 13                       |
| 91         | DGM Racing x JIM       | Mason Maggio & Myatt Snider    | 4                  | 11                       |
| 7          | JR Motorsports         | Justin Allgaier                | 4                  | 1                        |
| 18         | Joe Gibbs Racing       | William Sawalich               | 4                  | 4                        |
| 28         | RSS Racing             | Kyle Sieg                      | 3                  | 8                        |
| 00         | Haas Factory Team      | Sheldon Creed                  | 2                  | 25                       |
| 38         | RSS Racing             | Patrick Emerling               | 2                  | 35                       |
| 1          | JR Motorsports         | Carson Kvapil & Connor Zilisch | 2                  | 2                        |
| 92         | DGM Racing x JIM       | Josh Williams                  | 2                  | 28                       |
| 07         | SS GreenLight Racing   | Josh Bilicki                   | 2                  | 12                       |
| 51         | Jeremy Clements Racing | Jeremy Clements                | 2                  | 10                       |
| 26         | Sam Hunt Racing        | Dean Thompson                  | 1                  | 14                       |
| 0          | SS GreenLight Racing   | Garrett Smithley               | 1                  | 6                        |
| 88         | JR Motorsports         | Rajah Caruth                   | 1                  | 9                        |
| 96         | Viking Motorsports     | Anthony Alfredo                | 1                  | 5                        |
| 32         | Jordan Anderson Racing | Tyler Ankrum                   | 1                  | 27                       |
| 35         | Joey Gase Motorsports  | Natalie Decker                 | 1                  | -                        |
| 74         | Mike Harmon Racing     | Dawson Cram                    | 1                  | -                        |
| 02         | Young's Motorsports    | Ryan Ellis                     | 1                  | 23                       |
| 45         | Alpha Prime Racing     | Lavar Scott                    | 1                  | 21                       |
| 47         | Mike Harmon Racing     | Dawson Cram                    | 1                  | 36                       |

## Trucks: LiUNA 150

![Trucks @ Lime Rock Park 2026 | Credit: NASCAR.com](https://github.com/joeah99/Statcar_Images/blob/main/2026_Season/Atlanta(2)_Lime_Rock/Trucks%20Lime%20Rock%20Enfinger.jpg?raw=true)

Leave it to the NASCAR Truck Series to have significantly bigger upsets across the whole field on a road course than either of the superspeedway races this weekend. But, after the madness at San Diego a few weeks back, I shouldn't really be surprised. The top two stats correlated to finishing position were pit crew related...at a race with no competitive pit stops. Nonetheless, green flag pit stop times are an indicator of team funding, so it's not entirely surprising to see them at the top of the rankings. 

But in third place, we have long term mechanical failure rate once again, and even more confusingly, it is inversely correlated, unlike the Cup Series (meaning drivers with higher mechanical failure rates finished better at Lime Rock). To try to make sense of this, I looked at each of the past 10 road course races and made note of which drivers in the field last weekend had a mechanical failure in at least one of them: 

Christian Eckes, Parker Kligerman (3), Wesley Slimp (2), Kaden Honeycutt, Tanner Gray, Grant Enfinger, Jake Garcia, and Stewart Friesen. 

And to top off this weekend of coincidences, four of those eight drivers finished in the top 5 at Lime Rock, and six of them finished in the top 10! 

That's not even to mention that start-in-the-rear penalties in recent weeks were also a top indicator of finishing position at Lime Rock; that is, drivers who had to start in the rear in recent weeks were actually more likely to have a good finish last weekend.

### Top 10 Stats Correlated to Finishing Position (Lime Rock Park 2026)

| rank | feature                                    | raw_correlation | abs_correlation |
|:----:|:------------------------------------------:|:---------------:|:---------------:|
| 1    | avg_green_pit_crew_roll5_track             | 0.4929953185    | 0.4929953185    |
| 2    | avg_green_pit_crew_roll3_track             | 0.4929953185    | 0.4929953185    |
| 3    | mechanical_failure_roll10_tracktype        | -0.4889142857   | 0.4889142857    |
| 4    | avg_green_pit_crew_lag1_track              | 0.4602006688    | 0.4602006688    |
| 5    | start_in_rear_roll3_general_carteam        | -0.4331665501   | 0.4331665501    |
| 6    | start_in_rear_lag1_tracktype_carteam       | -0.4118113645   | 0.4118113645    |
| 7    | start_in_rear_lag1_general_carteam         | -0.4118113645   | 0.4118113645    |
| 8    | is_top_10_lag1_track                       | 0.3680088454    | 0.3680088454    |
| 9    | avg_yellow_pit_crew_lag1_track             | 0.3431639893    | 0.3431639893    |
| 10   | avg_yellow_pit_crew_roll30_general_carteam | 0.3419117647    | 0.3419117647    |


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