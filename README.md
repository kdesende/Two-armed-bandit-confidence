# Two-armed-bandit-confidence
This repo contains the data of a two-armed bandit tasks with additional confidence ratings, and code to analyse these data

# twoArmedBandit_with_confidence.csv
This file contains the raw (i.e. not preprocessed) empirical data, with one line per trial and one column per variable. The following variables are included:
'sub' participant ID
'condition' the variability condition (note, hc=low variability, lc=high variability)
'cond' the variablity condition coded as 0 (high variability) and 1 (low variability)
'cresp' which response would have given a p(high reward)  
'resp' which response did the participant give 
'cor' did the participants give the correct response (1=yes,0=no)
'rt' the reaction time of choice in s
'cj' confidence judgment (continuous value between 1 and 5)
'reward' the reward presented to the participant
'rtcj' confidence reaction times in s
'phase' the phase of the experiment (two levels= "induction" and "test")
'trial' trial counter within a mini-block
'trial_rev' reversed trial counter within a mini block
'Lreward' the reward associated with the left bandit
'Hreward' the reward associated to the right bandit
'correctAns' 
