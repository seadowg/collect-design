# Repeats

This is motivated by a narrative emerging on the forum around changes people want to make to repeats in Collect.

## Goals

The questions we want to know the answers to for this research round are:

* What kinds of questions are being answered (data is being collected) using repeats?
* What pain points are form designers witnessing with repeats?
* Are there tweaks to repeats we can make to make them better?
* Are there any new features we could build or reworks we could carry out that would provide better solutions than the current repeats feature?

## Plan

- [x] Use forum posts to collect initial research (using "insight/opportunity/pain point" format)
- [x] Write interview script with [goals](#goals) and initial research as input
- [x] Perform interviews with 3-5 form designers using script
- [x] Break each interview into "insight/opportunity/pain point" format
- [x] Synthesize (pull out common items) results of interviews and attempt to answer questions

## Interview script

1. I'm [your-name] and I'm doing some research into people using ODK tools for the ODK community.
1. This is a fairly informal conversation. The goal is just to get a better sense of how you use ODK tools. There aren’t any right or wrong answers here - your experience is the most interesting thing. We'll share the anonymized insights from this interview with the community to help us to continue to develop ODK.
1. Are you happy to be recorded?
1. Would you be able to tell me about your day to day job?
1. Could you tell me about the last time form you made as part of programme? Go into detail about the form and what XLSForm features you used.
1. Do you ever use repeats as part of your forms? If so, tell me about the last time you did?
1. What went well? What didn't?
1. Did repeats let you collect the data you needed?
1. Had you used repeats on other forms before this one? How different were they?

## Results

Research board is [here](https://miro.com/app/board/o9J_kw4mjM8=/).

* What kinds of questions are being answered (data is being collected) using repeats?
  * "Census" structure household data - having everyone in household, school etc answer same questions
  * Observation data - observing features of a location or entity
* What pain points are form designers witnessing with repeats?
  * It's hard for enumerators to add a new repeat group quickly when they are half way through another. This complicates data collection where repeats aren't filled out entirely in order (taking a list of names of people up front).
  * There can be confusion around the language used when prompting enumerators to add another group. the "group" is typically named ("observation" for example) and so the word itself seems to be complicating things ("add another observation group").
  * Some enumerators find navigating between repeats confusing.
* Are there tweaks to repeats we can make to make them better?
  * Fix "Add new group" dialog closing on app background
  * Improve the language around repeats in Collect better. On the "Add new group" prompt we could tweak it so that it puts more prominence on the repeat group label by removing the "group" word altogether. 
  * Revise navigation back through repeat instances. This would be really helped with field visits to see Enumerators work with repeats.
  * Look at adding the ability to add a new group from within a group (could be within the options menu).
  * Revise documentation to highlight using multiple form instances instead of repeats where appropriate.
* Are there any new features we could build or reworks we could carry out that would provide better solutions than the current repeats feature?
  * A way to reference form data from other forms could mean more people would use multiple form instances rather than repeats.
  * Being able to fill out one form within another instead of a repeat group (i.e. an observation can be made with a animal or plant form) would remove the need for form designers to use a lot of skip logic/hiding.
  * An alternative to the above would be a way of grouping forms within some project/task/workflow. An example would be a "household" project/task that groups several "member" forms together.
