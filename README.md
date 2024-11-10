# tasting-session
Visualise the results of your tasting session for wine, cider, champagne using graphs

## How to run

Run `plot.ipynb` to generate graphs for the template taste session. Requires python3

## How to create a new tasting session

1. Copy `data/template/` into your own folder `data/<my-tasting-session>`.
2. Edit `subjects.json` to represent the subjects to be evaluated
3. (Host your tasting session and have everyone note their scores)
4. Edit `scores.csv` to represent the testers' scores
5. Edit `plot.ipynb` to take `<my-tasting-session>` as input and run all cells