# The Impact of the Extract Method Revealed through the Eyes of Novices in Java
José Aldo Silva da Costa · Rohit Gheyi 

## Overview
Developers extract methods in the code aiming to make it easier to read, understand, and reuse. Through static code metrics, a previous study has shown that the Extract Method can have a negative impact introducing code smells. However, we lack studies investigating the impact of Extract Method using a dynamic perspective of human subjects, such as the visual effort, especially in the context of novices. We evaluate the extent of the impact of Extract Method on code comprehension from the perspective of the eye tracking metrics with novices in Java. We conduct a controlled experiment with 32 subjects. Each subject has the task of specifying the correct output of eight programs, four with the method inlined and four with the method extracted. We compare the tasks measuring the time, accuracy, and the subjects' visual effort with fixation duration, fixations count, and regressions count. In addition, we triangulate these quantitative results with the subjects' answers in a qualitative interview. With the Extract Method, there was a significant reduction in the time in the AOI of two tasks, which varied from 70% to 78.8%. We observed an increase in the accuracy of three tasks, which varied from 20% to 34.4%. Regarding the visual metrics, we observed a reduction in the duration of the fixations of three tasks varying from 73.6% to 78.9%, fixations count varied from 67.7% to 75.8%, and regressions count varied from 74.4% to 84.6%. On the other hand, with the Extract Method, there was an increase in the time of two tasks, varying from 108.4% to 166.9%. We observed an increase in the duration of the fixations of two tasks varying from 73.1% to 130.1%, fixations count varied from 137.1% to 194.2%, and regressions count varied from 100% to 200%. However, in the interview, the subjects found the tasks with Extract Method easier to solve than with the Inline Method. From the coding of their answers, we learned that extracting a method favors the formulation of the hypotheses about the behavior of the code. Extracting a method, for some tasks, made the code easier to understand, while it also hampered the understanding for other tasks, from the perspective of visual metrics. These results raise the awareness of educators about the Extract Method and its potential to ease or hinder the code comprehension for novices in Java. For researchers, these results show the potential of visual metrics to reveal an impact of refactorings that cannot be captured by static code metrics. 

Keywords: extract method · eye tracking · code comprehension 

## Experiment Material

All the experiment material is available <a href="https://github.com/josealdo/refactorings-with-eye-tracking/tree/main/Experiment%20Material">here</a>.

## Collected Data

The dataset wth the collected data is available <a href="https://github.com/josealdo/refactorings-with-eye-tracking/tree/main/Collected%20Data">here</a>.

## Results

All tables summarizing the results are available <a href="https://github.com/josealdo/">here</a>.
