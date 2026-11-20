# Developing a Neural Network Classification Model
print("Confusion Matrix:\n",conf_matrix)
print("Classification Report:\n",cl_report)
import seaborn as sns
x1=["A","B","C","D"]
sns.heatmap(conf_matrix,annot=True,fmt='d',cmap="Blues",xticklabels=x1,yticklabels=x1)
plt.xlabel("Predicted")
plt.ylabel("Actual")
plt.title("Confusion Matrix")
plt.show()





```

### Dataset Information
<img width="1305" height="953" alt="image" src="https://github.com/user-attachments/assets/a77194a8-94c7-4607-b7dc-2c5a556b1d8f" />


### OUTPUT

<img width="1637" height="564" alt="image" src="https://github.com/user-attachments/assets/f5fb381a-2b40-4df1-bca7-03dfa0a8568c" />

<img width="998" height="149" alt="image" src="https://github.com/user-attachments/assets/2ffb1ee6-8175-4698-b4d8-aa415544f108" />

<img width="1724" height="607" alt="image" src="https://github.com/user-attachments/assets/78268d99-ab8f-40b1-b80f-077a7789997b" />

<img width="1636" height="587" alt="image" src="https://github.com/user-attachments/assets/87617723-4d38-416c-a45b-da6d915e45dd" />

<img width="1608" height="604" alt="image" src="https://github.com/user-attachments/assets/bd574126-2ad3-4617-9b08-a7819b40a61b" />

<img width="360" height="852" alt="image" src="https://github.com/user-attachments/assets/9b66c1b6-6ae2-4c42-984c-d8f0d184f772" />






## Confusion Matrix

<img width="680" height="563" alt="image" src="https://github.com/user-attachments/assets/6cce4423-698c-4dd4-8b59-5b7aec29237e" />


## Classification Report
<img width="782" height="620" alt="image" src="https://github.com/user-attachments/assets/afffec0e-d640-4b5d-bf66-ed7050921751" />




## RESULT
Therefore, a neural network classification model has been developed for the given dataset.
