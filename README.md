# Two-armed-bandit-confidence
This repo contains the data of a two-armed bandit tasks with additional confidence ratings, and code to analyse these data

# twoArmedBandit_with_confidence.csv
This file contains the raw (i.e. not preprocessed) empirical data, with one line per trial and one column per variable. The following variables are included: <br />
'sub' participant ID <br />
'condition' the variability condition (note, hc=low variability, lc=high variability) <br />
'cond' the variablity condition coded as 0 (high variability) and 1 (low variability) <br />
'cresp' which response would have given a p(high reward) <br />  
'resp' which response did the participant give  <br />
'cor' did the participants give the correct response (1=yes,0=no) <br />
'rt' the reaction time of choice in s <br />
'cj' confidence judgment (continuous value between 1 and 5) <br />
'reward' the reward presented to the participant <br />
'rtcj' confidence reaction times in s <br />
'phase' the phase of the experiment (two levels= "induction" and "test") <br />
'trial' trial counter within a mini-block <br />
'trial_rev' reversed trial counter within a mini block <br />
'Lreward' the reward associated with the left bandit <br />
'Hreward' the reward associated to the right bandit <br />
'correctAns'  <br />
