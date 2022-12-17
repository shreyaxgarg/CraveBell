# CraveBell - A mood-based food recommendation system
The aim of this system is to give food suggestions to the user according to his/her mood and map the users’ choice of food to the place where they can be availed the best. With a vast variety of food and an overwhelming number of restaurants providing those dishes, its common to face a tough time to decide what to eat. Our system would try to help the user to select the food that he/she would like to order and would also suggest the preferable restaurants serving those dishes.

## Methodology
![image](https://user-images.githubusercontent.com/75696894/208227268-4e4af461-1ae3-419c-90a5-5319191b5852.png)

## Working and Implementation
Dataset used: Zomato Restaurant Dataset
<br>Model used: Logistic Regression
<br><br>•The major feature of our project which sets it apart from the traditional apps of its kind needs three parameters to order the list of recommended restaurants with the highly recommended restaurant at the top. These three features are the user ratings, cost for two people and the restaurant's distance from the user.
<br> &nbsp; •Whenever any user orders from a certain restaurant, he/she is asked to rate the restaurant out of 5. The rating of that restaurant is then dynamically updated using the mathematical average of the current rating and the new rating. This computation also requires the storage of the number of ratings for a particular restaurant.
<br> &nbsp; •The cost for two people is permanently stored initially when a restaurant is added to the database.
<br> &nbsp; •To compute the distance of the user from a restaurant, we have stored the geocode of all the restaurants in the database. We have used the Google Maps API to extract the user's geocode and hence compute his/her distance.
<br>A very simple model of machine learning, that is logistic regression is used to implement the same. When the user chooses a certain restaurant among the recommended restaurants, then his/her choice to select a certain restaurant and discard other restaurants is used to train the model which only increases the accuracy of the algorithm.
<br>•The USP of our project, which is recommending the users food items based on their mood works on previous users' inputs only. Whenever any user orders from a certain restaurant, he/she is asked to specify what his/her mood was before he/she had ordered. His/Her order and mood is used to train the algorithm which gradually increases its accuracy.
<br>•To help small businesses expand their reach by selling on our application, we have simply provided them with a form wherein they can fill out the necessary details.

## Screenshots of the Interface

![image](https://user-images.githubusercontent.com/75696894/167893343-6ac6bc12-3208-4667-8536-3f4507603b3b.png)

![image](https://user-images.githubusercontent.com/75696894/167893414-efd1d5ad-6760-4926-925b-f6d4e6304b73.png)

![image](https://user-images.githubusercontent.com/75696894/167893550-09e363a2-5375-4873-9602-e2abf53c0fd6.png)

![image](https://user-images.githubusercontent.com/75696894/167893592-75c2b317-5402-4c01-bc77-84d13f3ce717.png)

![image](https://user-images.githubusercontent.com/75696894/167894188-a9142f46-be77-40a2-b696-a14af3179cce.png)

![image](https://user-images.githubusercontent.com/75696894/167894430-912baba6-39ed-4671-9eae-88608e7ba6f5.png)
