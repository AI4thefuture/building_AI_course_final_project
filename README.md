# Workplace wellbeing predictor (WWP)

Final project for the Building AI course

## Summary

The WWP gauges the wellbeing in a workplace and predicts the level of workplace wellbeing.
The level of workplace wellbeing can be used to determine whether intervention is required and higlight the potential sources for
the positive or negative result. 

## Background

Wellbeing in the worplace is important! I belive that employees that work in a physically and psychologically safe and positive enviroment will perform better,
need less sick leave, and be less likely to quit their job. A good reputation will also make the workplace attractive and recruting
suitable candidates will be easier.
The WWP solves the problem of objectively gauging the level of wellbeing in the workplace. Too often the wellbeing in a workplace is low
without anyone acknowleding the situation and thus not acting to improve it. 
The WWP could help organisations use their available data to get an objective measure the level of wellbeing
in the organisation and list possible improvements. It could also help with early identification of problems so that they can be addressed at an early stage.
If data is not available suggestions for what type data to gather would be recommended.
The WWP could also have parameters linked to the type of work being performed etc.

## How is it used?
 # Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

I imagine that the The WWP could be used as follows:
1. Available data from the organisation is mapped and compared to the minimum input requirements 
2. The applicable data is structured and used as input. 
3. Based on the input the WWP predicts that status of the wellbeing in the organisation and suggests steps for improvement.
4. The tool is then ideally used at regular intervalls (or when new data is available) to check for positive or negative trends.

Users would typically be human resource departments monitoring the health of the organisation.  

## Data sources and AI methods
 # Where does your data come from? Do you collect it yourself or do you use data collected by someone else?

For this project machine learning (or a nevral nettwork) could be used. The model would be trained on data from actual organisations (if available) or data
constructed based on research into workplace wellbeing and burnout.
        
The data for the predictions would come from the organisations themselves e.g. employee surveys, employee/company statistics etc.

## Challenges
 # What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

There are plenty of challenges for this project and a lot of questions that need to be answered, and obviously there are some ethical considerations
that would need to be clarified as well.

Typical questions that would need to be answered:
- What is wellbeing?
- How can wellbeing be quantified?
- What parameters are important for objectively gauging wellbeing
- How can the data be collected?
- How can the data be presented to ensure that no individals can be identified?

Establishing the data for training the model could also prove challenging.

## What next?
 # How could your project grow and become something even more? What kind of skills, what kind of assistance would you need to move on? 

A good starting point for this project would be to address the questions stated above. 
This would serve as a basis for collecting training data.
In parallell with the data collection some coding should be done to get an impression of how the WPP could be trained and what features it could have.

## Acknowledgments

* list here the sources of inspiration :
    This project is inspired by the helplessness that employees feel when the working enviroment is poor and workplace wellbeing is low. All the employees may
    know that something is not working, but nobody is willing (or able) to voice their discontent. Typically the only way out is for the employee is to endure the
    torment or quit for a more promissing job somewhere else.
