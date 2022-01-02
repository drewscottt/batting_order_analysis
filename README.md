## Description:
Simulates every possible batting order for a given lineup and displays summary statistics of
the average runs (over a number of games) of the orders, and specific information about the
top and bottom 5 orders. The user may choose how many games each order is simulated for,
which players are in the lineup, or what each player's PA outcomes are in a single game
(see sample files).

## Data Source
[Baseball Savant Custom Data](https://baseballsavant.mlb.com/leaderboard/custom?year=2021&type=batter&filter=&sort=0&sortDir=desc&min=50&selections=b_total_pa,b_single,b_double,b_triple,b_home_run,b_strikeout,b_walk,on_base_percent,on_base_plus_slg,b_catcher_interf,b_hit_by_pitch,b_out_fly,b_out_ground,b_out_line_drive,b_out_popup,r_caught_stealing_2b,r_caught_stealing_3b,r_caught_stealing_home,r_stolen_base_2b,r_stolen_base_3b,r_stolen_base_home,woba,pull_percent,straightaway_percent,opposite_percent,&chart=false&x=b_total_pa&y=b_total_pa&r=no&chartType=beeswarm)

## Major TODOs:
    1) Determine the accurate likelihoods of sacrifices and double plays for different out types
    2) Enable some sort of pinch hitting scheme (right now, each player hits the entire game)
    3) Enable some sort of pitcher dependent hitting results (even as simple as right-y/left-y;
        right now hitting stats are full season aggregates)
    4) Include edge cases like stealing, wild pitches, etc.
    5) More detailed data (i.e. did a double go to right or left field?)
    6) Player specific data (i.e. how often does a player try to steal?)

## Installation:
    pip install batting-order-analysis
[View on PyPI](https://pypi.org/project/batting-order-analysis/)

## Usage:
    driver.py supplies a basic front-end, read its usage there
