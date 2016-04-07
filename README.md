# Commenting System Domain Model

## Introduction
Physical fitness and a healthy lifestyle has grown in leaps and bounds over the last decade with more people striving to live healthier longer lives.The introduction and popularity of wearables like Fitbit, Jawbone and Nike's Fuelband has shown that there is devenately a large not yet fully explored market in the technology sector for products aimed at health and fitness. Currently the average person is unable to get the benifits of a well laid out exercise routine without purchasing one of the expensive above mentioned wearbles or paying exuberant fees for a personal trainer, this application aimes to solve that problem by providing the user with a unique workout plan designed to suit his or her needs.  



## Class Diagram of the Domain Model

Below is the class diagram of the workout plan application i want to develop.

![Domain Model](/GymModel.jpg)

## Description of the Domain Model and its Invariants

According to the Domain Model, each user will be able to create either a custom workout plan, according to his or her physical fitness or preference, or have one created for them by the application.

When the the user chooses to create their own workout plan there will be no need for them to enter any personal information other than their email address, screen name and password.This is only so their custom plan can be linked to their profile. They then have the freedom to choose which body part they wish to exercise and on which day of a seven day cycle.They are able to exercise one part on one day or the same part for an entire cycle, the choice is theirs.When choosing a body part to exercise, they will be presented with the options of the different muscle groups in that specific part, visual aids of the muscles the exercise is targeting, as well as hints on their form for doing that specific exercise correctly.They are then able to choose not only the body part but the muscle or muscle group within that part they wish to exercise. This information is then stored in a database. The users will also be able to choose if they want the same pattern of workouts repeated for consecutive cycles or have the system generate random exercises for the body parts they chose.    

When the user opts for the generated workout plan he or she will have to enter additional information first before the system can generate a plan catering to their specific body type and fitness level. The first section will require them to enter their age, gender, height and weight.The second section will present them with options of different body types of which they must choose one. The third section will ask them a number of questions in order to determine their fitness level.The final section will calculate their body mass index by asking them to enter some physical information about themselves. The system will then use this information to generate a workout schedule based on a seven day cycle that is unique to the user. This schedule will stretch over a minimum length of one month, to a maximum length of one year, with the user being able to specify the specific length. At any point during the cycle the user can request a different exercise but on the same body part, this is to keep the plan from becoming mundane and the user loosing interest.

Users will also be allowed to look up a specific exercise without the need to create a generated workout plan first.They will have excess to the workouts database and be able to look up information about any exercise of their choosing.

To add to their new healthy lifestyle they will be given access to a calorie counter, carbohydrate counter as well as a protein counter. They will be able to access these at any time without the need to first enter any physical details. In order to get the amount of calories, protein or carbohydrates in any food they need only identify the food type on the given list, enter the portion size they which to consume and how many servings thereof. The system will then process the given information presenting them with calorie, protein or carbohydrate count of that specific food portion.    