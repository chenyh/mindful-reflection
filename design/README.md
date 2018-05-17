# Data Model

Entity Relation

![eflection Note](https://drive.google.com/uc?export=download&id=1iIss5NREcxIahppS7O52gDPkqC0QGFdp)



Note:

- status: 
  - active: actively in the spaced repetition cycle
  - inactive: not in the cycle
  - pinned: always in the cycle
- spaced(in `note`): the actual start time for the spaced repetition, default to the created time of note, could be reset to the current time if the user want to restart a round

# Reflection Algorithm

Predefined [spaced repetition cycle](http://www.revunote.com/resources/spaced-repetition-2/): 1, 2, 7, 30

