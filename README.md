
# Tiktok - ML - Graphical User Interface - Random Forest - Extreme Gradient Boosting - Classification Model

## Introduction:

In the vibrant and fast-paced world of TikTok, our mission is to inspire creativity and bring joy to millions of users worldwide. As our platform continues to grow rapidly, so do the challenges associated with moderating content to ensure a safe and enjoyable experience for all users. One such challenge is the timely and effective review of user reports, particularly those related to identifying videos and comments containing claims.

The current process of reviewing user reports generates a large volume of data that is challenging to handle efficiently. This backlog not only strains our moderation resources but also impacts the overall user experience. To address this issue, TikTok is actively working on the development of a predictive model that can automatically identify videos containing claims or opinions. By implementing such a model, we aim to streamline the moderation process, reduce the backlog of user reports, and prioritize them more effectively.

This project represents a critical initiative within TikTok's data team, as we strive to leverage machine learning techniques to enhance the platform's content moderation capabilities. In the following sections, we will outline the remaining tasks necessary to complete the claims classification project, including model building, evaluation, and summarizing findings for cross-departmental stakeholders. By successfully implementing this final machine learning model, we aim to make a tangible impact on TikTok's ability to maintain a safe and engaging environment for our diverse community of users.

## Problem Statement:
#### TikTok faces a challenge in efficiently moderating user-generated content due to the overwhelming volume of user reports; a predictive model for claims classification is being developed to automate identification, reducing backlog and enabling prioritized moderation.

## Objective
Developing a machine learning model for claims classification will streamline content moderation on TikTok, enabling timely identification of videos containing claims or opinions, thereby improving efficiency and enhancing user experience.

The following tasks are needed to complete the project:

    Exploratory Data Analysis (EDA)

    Model building

    Model evaluation

    Summarize findings for Tiktok and the stakeholders .

# Business need and modeling objective

TikTok users can report videos that they believe violate the platform's terms of service. Because there are millions of TikTok videos created and viewed every day, this means that many videos get reported—too many to be individually reviewed by a human moderator.

Analysis indicates that when authors do violate the terms of service, they're much more likely to be presenting a claim than an opinion. Therefore, it is useful to be able to determine which videos make claims and which videos are opinions.

**TikTok wants to build a machine learning model to help identify claims and opinions.** Videos that are labeled opinions will be less likely to go on to be reviewed by a human moderator. Videos that are labeled as claims will be further sorted by a downstream process to determine whether they should get prioritized for review. For example, perhaps videos that are classified as claims would then be ranked by how many times they were reported, then the top x% would be reviewed by a human each day.

A machine learning model would greatly assist in the effort to present human moderators with videos that are most likely to be in violation of TikTok's terms of service.

# Modeling design and target variable

The data dictionary shows that there is a column called claim_status. This is a binary value that indicates whether a video is a claim or an opinion. This will be the target variable. In other words, for each video, the model should predict whether the video is a claim or an opinion.

`This is a classification task because the model is predicting a binary class. Select an evaluation metric`

To determine which evaluation metric might be best, consider how the model might be wrong. There are two possibilities for bad predictions:

    False positives: When the model predicts a video is a claim when in fact it is an opinion
    False negatives: When the model predicts a video is an opinion when in fact it is a claim


## 🛠 Skills

ML Model :  Classification Model
        
        Extreme Gradient Boosting

        Random Forest Classifier

Leveraged Jupyter Notebooks along with libraries such as 

    - pandas
    - numpy
    - matplotlib
    - seaborn
    - scikit-learn
    - xgboost
    - pickle



## 🔗 Connect with Me

Feel free to connect with me on :

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://parthebhan143.wixsite.com/datainsights)

[![LinkedIn Profile](https://img.shields.io/badge/LinkedIn_Profile-000?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/parthebhan)

[![Kaggle Profile](https://img.shields.io/badge/Kaggle_Profile-000?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/parthebhan)

[![Tableau Profile](https://img.shields.io/badge/Tableau_Profile-000?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/parthebhan.pari/vizzes)

