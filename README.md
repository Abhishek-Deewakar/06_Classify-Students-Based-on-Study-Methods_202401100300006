Students have different ways of learning—some prefer visual aids, others learn better by listening, and some through hands-on activities. These are known as learning styles: visual, auditory, and kinesthetic.  
Classifying students based on their study methods helps in providing personalized learning strategies. In this study, we use students' scores in each learning style and apply machine learning to predict their preferred method. This can improve teaching effectiveness and student performance._______




we use bar grap to show result


plt.figure(figsize=(25, 12))
df_melted = df.melt(id_vars=["Student_ID"], value_vars=["Visual", "Auditory", "Kinesthetic"],
                    var_name="Style", value_name="Score")
sns.barplot(data=df_melted, x="Student_ID", y="Score", hue="Style", dodge=True)
plt.title("Student Scores by Learning Style", fontsize=14)
plt.xlabel("Student ID", fontsize=12)
plt.ylabel("Score", fontsize=12)
plt.xticks(rotation=0)
plt.legend(title="Style")
plt.tight_layout(pad=3.0)
plt.show()

