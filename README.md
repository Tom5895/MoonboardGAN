# MoonboardML
The MoonBoard is a standardised interactive rock climbing training wall that connects a global community of climbers through shared problems and competitive performance rankings. climbing problems can be set on the MoonBoard as shown in Figure 2 and added to an online database. In this way, climbers from around the world can participate in an online community where problems are created, shared, and rated. Problems are also given a difficult rating (grade) by given by the route setter and a crowd sourced grade given by the community, who have also climbed the route.

<img src="moonboard.jpg" alt="a moonboard" width="300"/>

The figure below shows an image of a moonboard problem. The climber must reach the final hold using only the circled holds for their hands and feet.

<img src="moonboardproblem.png" alt="a moonboard problem" width="300"/>

Throughout this project we build a classifier to predict the grade of a MoonBoard problem given only the specific holds used. We compare the performance of a Convolutional Neural Network against a Long Short-Term Memory Network which is able to capture additional information from the order in which the holds are used when climbing the problem. 

We also experiement with a Variational Auto-Encoder to autonomously generate new moonboard problems

The data was scraped from the MoonBoard website using Selenium WebDriver.
