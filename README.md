# Random Dot Motion (RDM) Task
## Overview
This experiment implements a Random Dot Motion (RDM) task, also known as a Random Dot Kinematogram (RDK), designed to measure motion perception thresholds and decision-making processes. Participants view a circular field of moving dots and must judge the overall direction of coherent motion (left or right) while varying levels of noise are present.
## Task Description
What Participants See

A circular aperture containing 150 white dots on a black background
Some dots move coherently in one direction (signal dots)
Other dots move randomly (noise dots)
Participants must identify whether the coherent motion is leftward or rightward

## Trial Structure

Fixation Cross (0.5-1.5 seconds): Participants focus on a central fixation point
Motion Stimulus: Dots appear and continue moving until a response is made
Response: Participants press arrow keys to indicate perceived direction
Inter-trial Interval (0.5 seconds): Brief blank screen before next trial

## Experimental Design

Motion Coherence: 5 levels (5%, 10%, 20%, 40%, 80%)

Lower coherence = harder to detect motion direction
Higher coherence = easier to detect motion direction


Motion Direction: 2 levels (0° = rightward, 180° = leftward)

## Dependent Variables

Accuracy: Whether response matches actual motion direction
Reaction Time (RT): Time from stimulus onset to response

## Trial Count - User Defined

In experiment info box the user enters the trial information
The code will generate a set of trials containing an equal number of coherence and direction settings
Trials are randomly ordered to prevent anticipation effects

## Stimulus Parameters
Number of dots = 150
Dot size = 5 pixels 
Dot speed = 0.5°/frame

## Response Instructions

LEFT Arrow: Indicate leftward motion
RIGHT Arrow: Indicate rightward motion
ESC: Exit experiment (emergency exit)

Participants should respond as quickly and accurately as possible once they perceive the motion direction.

## Output Data
The experiment saves two files with timestamp:

Excel file (participantID_random_dot_motion.xlsx)


## Data Columns

coherence: Motion coherence level for that trial
direction: Actual motion direction (0 or 180)
correct_response: Expected response ('left' or 'right')
response: Participant's actual response
rt: Reaction time in seconds
correct: Boolean indicating if response was correct
fixation_duration: Duration of fixation period

## My Modifications
For this task, I modified the appearance of the random dot stimulus.
The dots are larger, red, and displayed in a square field instead of a circular one.
This change makes the motion easier to see while keeping the experimental logic identical to the original.


