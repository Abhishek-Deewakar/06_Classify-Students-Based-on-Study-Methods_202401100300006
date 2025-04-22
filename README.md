Students have different ways of learning—some prefer visual aids, others learn better by listening, and some through hands-on activities. These are known as learning styles: visual, auditory, and kinesthetic.  
Classifying students based on their study methods helps in providing personalized learning strategies. In this study, we use students' scores in each learning style and apply machine learning to predict their preferred method. This can improve teaching effectiveness and student performance._______

Rule-Based Classification: The algorithm classifies students into learning styles based on their scores for Visual, Auditory, and Kinesthetic learning styles. Here's how it works:

Step 1: For each student, the code checks their scores for each of the three learning styles.

Step 2: It then compares the scores. If the difference between the highest and second-highest score is less than 1.0, the student is classified as "Multimodal" (meaning they have balanced preferences across multiple styles).

Step 3: If the difference is significant, the student is classified into the style with the highest score.


we use bar grap to show result
![image](https://github.com/user-attachments/assets/96ae1942-57b8-4ad6-a494-05755a8952e7)
we also use pie chart to show 
![image](https://github.com/user-attachments/assets/a2d06133-5053-4c4c-a899-20ef7c5330f2)

