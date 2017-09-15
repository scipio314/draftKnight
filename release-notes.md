### draftKnight v1.5
# Updated for the 2017 season  

**Data Connection**  
* Updated the URL for fantasypros ECR projections page.  

**If you have problems with refreshing projections try doing the steps outlined below to login to fantasypros inside Excel.**    

**Important steps to get the player projections to work:**  
1. Go to the "Data" tab in Excel and then select "Connections".  
2. Select "FPProjections" and click the "Properties" button.  
3. Go to "Definition" and then "Edit Query..."  
4. This will open the projections page. Select "yes" a ton of times.  
5. Once you click through the pop-up hell, hover your mouse over the left hand side and move up and down until you see "Log In".  
6. Select that and login to fantasypros with your credentials.  

You should only have to do this once. If this doesn't work go to [this issues thread](https://github.com/scipio314/draftKnight/issues/8) and report there. Someone may have a solution for you.   

**Players**  
* Created a script to update differences in player names (example: Mitchell Trubisky changes to Mitch Trubisky).  
* Michael Thomas changed to Mike Thomas to avoid confusion.  

### draftKnight v1.4  
**Custom Projections**  
* Fixed: All previous entries are removed before adding new player pool.  

**Optimization Results**  
* Fixed: Previous entries are removed when downloading a new player pool.  

**Performance**  
* Fixed: Now supports more than 100 entries.  
* Fixed: Graphs show more than 100 entries.  
* Fixed: Formatting bugs.  
* Fixed: .csv output file for a perfect lineup is now called "DKEntry - Perfect Lineup.csv" instead of "DKEntry - Post Optimal Lineup.csv"  

**My Team**  
* Fixed: WR's that get locked now appear darkened.  

### draftKnight v1.3  
* Added: There is now a column on the "My Team" page that shows the opponent the player is facing.  [#2](https://github.com/scipio314/draftKnight/issues/2)

### draftKnight v1.2  
* Fixed: workbook connections are now re-pathed to users folder directory.  

### draftKnight v1.1  
* Fixed: Optimal team now shows up up on "Performance" sheet  
* Fixed: Chart min and max values now adjust to results  
* Fixed: Comment markers are now deleted when refreshing "My Team" page (hopefully)  

### draftKnight v1.0  

Initial features of the excel workbook:  
* Just paste the DK link to the player pool and salary information is auto-imported.
* Auto DL latest player injury news.
* Uses FantasyPros ECR to generate X number of optimal lineups.
* Allows for custom projections as well.
* Lock certain players to include them in your lineup.
* Ignore players to exclude from them from your lineup.
* Track your progress using the actual points from the previous week.
