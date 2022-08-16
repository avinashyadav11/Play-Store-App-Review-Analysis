# Play-Store-App-Review-Analysis

## Introduction
The objective of this project is to deliver insights to understand customer demands better and thus help developers to popularize the product. To clarify, the ‘popular’ in this project means a high number of installations

## DATA SUMMARY:
The dataset contains details of Android applications present on Google Play Store. For analysis of the mentioned data, three we have used Python. Our business case is to locate the best Apps, which we measure by Review check. There are 13 includes that depict each application and an aggregate of 10842 applications. Following variables were initially included:
1. App – Name of the app
2. Category – Category of the app
3. Rating - Over all user rating of the app out of 5 on the Play Store 
4. Size – Size of app
5. Reviews – Number of user reviews for the app
6. Installs – Number of user downloads/installs for the app
7. Type – Paid or free
8. Price – Cost of the app
9. Content Rating – Age group the app is targeted at
10. Genres - An app can belong to multiple genres (apart from its main category)
11. Last Updated - Date when the app was last updated on Play Store
12. Current Ver. - Current version of the app available on Play Store
13. Android Ver. – Minimum required android version
## Key Findings from EDA
1. The average rating of apps on play store is 4.18.
2. Bulky applications are less installed by the user and this applies for both type of apps paid and free.
3. The median size of the apps in the play store is 12 MB.
4. Top 3 category of paid apps and free apps are same Family, Tools and game.
5. Percentage of free apps: ~92%

## Conclusion: 
1. The dataset contains possibilities to deliver insights to understand customer demands better and thus help developers to popularize the product. 
2. Dataset can also be used to look whether the original ratings of the app matches the predicted rating to know whether the app is performing better or worse compared to other apps on the Play Store. 
3. It is not limited to the problem taken into consideration for this project. Many other interesting possibilities can be explored using this dataset.


## Future Work
1. Prediction of the number of reviews and installs by using the regression model.
2. Identifying the categories and stats of the most installed apps.
3. Exploring the correlation between the size of the app, the version of Android, etc on the number of installs.
