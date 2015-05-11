# LambdaConf 2015 - Schedule Challenge Problem

How'd you like to win a **FREE** ticket to LambdaConf 2016 (*or* 2015)?

Here's your chance: announcing the LambdaConf 2015 - Schedule Challenge Problem!

**Note**: *This challenge problem is officially open from May 9, 2015 - May 11, 2015. If you want a chance to win free tickets, please make sure you submit your solution within this time frame!*

# Introduction

Prior to the conference, we have conducted our annual pre-conference survey. The results are cataloged below:

[LambdaConf 2015 Pre-Conference Survey](https://docs.google.com/spreadsheets/d/1wce5rPQ-g8I-cIkL_e2eVsau52m6OSe5uoKh5Xk4lfE/edit?usp=sharing)

There are two challenge problems we've created that focus on this data set:

 1. Data Mining
 2. Schedule Generation

Read below for details on each!

# 1. Data Mining

This challenge problem involves mining the data set for insights. While the set of questions is not fixed in advance, here are some obvious questions that could be answered by data mining:

* **Clustering**. What natural clusters emerge? What are the characteristics of these clusters? Is it purely static typing versus dynamic typing, or is the story more nuanced than that?
* **Time Correlations**. What are the characteristics of those who completed the survey early? Those who completed it late? Those who took a short time? Those who took a long time?
* **Popularity**. What are the most popular talks and workshops? The least popular? Can this information be used to say anything about the LambdaConf audience?
* **Sponsor Correlations**. Can knowledge of a sponsor be used to predict anything? Can lack of knowledge of a sponsor be used to predict anything?

We will award up to (5) free tickets to individuals or teams who submit entries to this challenge problem that we accept. Successful entries will include all code, methods, processes, and associated material, and will look beyond the surface and illustrate insights with carefully chosen data visualizations. Note that we are the sole judges of which entries we accept or reject, and we reserve the right to accept or reject an entry on any grounds whatsoever.

# 2. Schedule Generation

This challenge problem involves using the data set to produce a possible schedule for LambdaConf 2015.

The schedule should maximize attendee happiness, as defined by the following process:

 * For each day (Friday and Saturday), normalize each attendee's voting points to the range [0, 1]. That is, for each day, the sum of all the points an attendee awards all the content in that day must be equal to 1.0.
 * Define attendee happiness as the sum of all normalized attendee points for a given configuration of the schedule, assuming that attendees may attend at most one track per time slot.

You should assume that on Friday, all workshops will fit into 8 hours total, divided into multiple tracks, and that on Saturday, all presentations will fit into 8 hours total, divided into multiple tracks. The data set includes both the day (`F` = Friday, `S` = Saturday) as well as the length of every session (`30` = 30 minutes, `60` = 60 minutes, `120` = 120 minutes).

If you want to get fancy, you can take into account minimum, maximum, mean, mode, standard deviation, and other measures of attendee happiness, just be sure to explain and justify your scoring.

**Note**: Currently, due to a speaker conflict, the workshops *An Introduction to Rust: Or, "Who Got Types in My Systems Programming!"* and *An Adventure in Elm: Writing an Adventure Game in Elm* are being shifted into Sunday and should **not** affect Friday's schedule.

We will award up to (5) free tickets to individuals or teams who submit entries to this challenge problem that we accept. Successful entries will include all code, methods, processes, and associated material, together with one or more proposed and scored schedules for LambdaConf 2015. Note that we are the sole judges of which entries we accept or reject, and we reserve the right to accept or reject an entry on any grounds whatsoever.

# Submitting Your Entry

To submit your entry, simply Tweet a link to your submission to [@lambda_conf](http://twitter.com/lambda_conf), or send an email to John A. De Goes (john@degoes.net).