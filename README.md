# Samudra's Culture Code

This is a shorthand articulation of the ideal company culture that I'd like to be a part of, or help create. This is always going to be a work in progress.

## What the processes should look like

```
function move(fast=true, assumptions, priorData){
  if (fast==false) {
    smallerProblems = [];
    smallerProblems = breakdownIntoSmallerProblems(this);

    for problem in smallerProblems:
      problem.move(true, assumptions, priorData)
    
    return
    // see doICareAbout.codingLanguage  
  }
  
  assumptions.append(getExpertInsights(this.parent))
  priorData.append(getPriorExperimentData(this.parent))

  experimentResults = articulateHypothesis(assumptions, priorData).getData();

  if(iBrokeSomething == true){
    fixFast();
    askForForgiveness();
  }
  else {

    lessons = synthesize(experimentResults);

    scaleUp(lessons);

    teachOthers(lessons);
  }
}
```

## Do I care about...

```
doICareAbout = {
  "impacting mankind's trajectory": true,
  "solving the right problem": true,
  "solving the problem the right way": true,
  "design": true,
  "sociology": true,
  "user experience": true,
  "psychology": true,
  "lean": true,
  "peopleIWorkWith": true,
  "continuousLearning": true,
  "knowledge management": true,
  "online communities": true,

  "codingLanguage": false,
  "freeLunches": false,
  "theNextUberForDogWalkers": false
}
```
