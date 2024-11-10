# tasting-session
Visualise the results of your tasting session for wine, cider, champagne using graphs

## How to run

Run `plot.ipynb` to generate graphs for the template taste session. Requires python3

## How to create a new tasting session

1. Copy `data/template/` your own folder `data/<my-tasting-session>`
2. Edit `data/<my-tasting-session>/subjects.json` to represent the subjects to be evaluated 
3. (Host your tasting session and collect testers evaluation)
4. Edit `data/<my-tasting-session>/scores.csv` to represent the subjects to be evaluated
5. Edit `plot.ipynb` to take `<my-tasting-session>` as input instead, and run all cells