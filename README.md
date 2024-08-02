# Understanding College Student Movie Theatre Preferences


## Introduction

The objective of this research is to gain a comprehensive understanding of college students’ preferences, behaviors, and motivations related to movie theater attendance. By employing market segmentation, targeting and positioning techniques, it aims to identify distinct student segments, tailor marketing strategies, and enhance the overall movie-going experience.


## Data

The dataset originates from a comprehensive questionnaire administered to college students. Their responses provide valuable insights into attendance patterns, spending habits, and factors influencing theatre selection. The key variable are:

- Attendance Frequency: How often do college students visit movie theatres?
- Spending on Food Items: What is their expenditure on popcorn, candy, and other food items during movie outings?
- Factors Influencing Theatre Selection: Considerations such as screen size, sound quality, comfortable seating, and amenities.
- Distance Tolerance for “Big Screen” Theatres: How far are students willing to travel for premium viewing experiences?
- Preferred Information Sources: Where do students seek movie theatre information (e.g., newspapers, internet, friends)?
- Ticket Purchase Options: Percentages for online purchases, at-theatre purchases, and other options.
- Demographics: Ethnic background, gender, age, and classification.

## Research Questions

- **Segmentation**: How can we categorize college students based on their movie preferences, viewing habits, and demographic characteristics?
- **Targeting**: Which segments represent the most promising target audience for movie theaters?
- **Positioning**: How can theaters position themselves effectively to resonate with these segments?

## Method

The data has been analyzed in the following two methods:
- Descriptive Analysis
- Inferrential analysis

## Analysis & Interpretation 

**Descriptive Analysis**

In the initial phase of the study, I conducted descriptive analyses to gain insights into the data. Here are the key findings:

- **Movie Attendance**

    **Percentage of Attendees**: We calculated that approximately 90% of college students attended at least one movie in the last year.

    ![image](https://github.com/user-attachments/assets/c371538e-ee54-431a-94be-888b6cc2680b)

    **Frequency of Attendance**: Among those who attended, the average monthly movie attendance was 1.58 per month. This provides an overview of how often students engage with movie theatres.

    ![image](https://github.com/user-attachments/assets/52ec5aeb-a3c5-4c2e-a1d1-295b870a892a)

- **Factors in Selecting a Movie Theatre**

I used rank-ordered averages to identify the most important factors influencing movie theatre selection. These factors include amenities (e.g., comfortable seating, screen size), location, and other considerations. Understanding these preferences guides marketing strategies. Based on   the analysis, the five factors that college students prioritize the most ranking in an ascending order are: 

- Comfortable chairs 
- Quality od sound system 
- Clean restrooms 
- Size of Screen 
- Auditorium type seating

![image](https://github.com/user-attachments/assets/a501fba3-45a6-47ff-9b4a-bb7600170134)

- **Information Sources**

To optimize communication channels, I explored where college students are most likely to learn about what is playing at the movies. Common sources include internet, television, radio, phone etc., which can inform targeted advertising and outreach efforts.
Based on the data, the percentage of college students who find the information channels “very important” is as follows:

- Internet: 49.7% 
- Newspaper: 28.8% 
- Phone: 27.7% 
- Friends or Family: 25.4% 
- Television: 22.3% 
- Other sources: 6.2% 

![image](https://github.com/user-attachments/assets/9801301d-e1a4-41d3-9f82-0e7d15c88293)
![image](https://github.com/user-attachments/assets/7c55f3aa-7c07-40a2-a6de-7c7c339a67bd)


**Inferrential Analysis**

Here, I am first examining how age, gender, and their interaction influence the average number of movies college students attend at movie theaters in a month using a univariate ANOVA analysis. All analysis were ran considering the level of significance of 10%.
The interaction effect between gender and age was not significant (p= .43). Next, we look at the simple main effects. Only age (F (4,438) = 4.98, p <.01) has a significant impact on the average number of movies college students attend at movie theaters in a month. However, there was no effect of Gender on the number of movies watched (p=.22).

![image](https://github.com/user-attachments/assets/d0999242-d50d-4fd9-aaa1-329dbe391014)

Now, to understand the data structure to segment the market, I have first conducted a factor analysis to reduce the number of items in questions 5a to 5i to a set of factors, where each of them represents different group of items that are important in selecting a movie theatre. Thereafter I named each factor and saved the factor scores. 

![image](https://github.com/user-attachments/assets/db863f0b-66bc-4ca0-9aa1-9a0de4dcbbd1)

![image](https://github.com/user-attachments/assets/b00079a8-b3ad-4edc-911b-33f63e7c1160)

![image](https://github.com/user-attachments/assets/8db7694c-1634-4ea3-bf25-4c29dbef9e97)

The factor analysis resulted in a three-factor solution with eigen values for each of them greater than 1 as the criteria. The scree plot confirms this as well. The total variance explained for the three-factor solution is 70%. Next, to make sure that we have unique factors, we selected items that had a factor loading greater than 0.6 on the particular factor and lower than 0.3 on the other factors in the rotated component matrix. We found that for Factor 1: items 5d-5h, for Factor 2: items 5b, 5c and 5i, and for Factor 3: item 5a, satisfied the criteria.  Next, we named the factors based on the items that loaded on each of them as follows:

- **Quality, Ambiance, and Amenities Focused Customers**: We find high factor loadings (FL) for ‘Size of screen(s)’ (FL 0.864), ‘Quality of sound system’ (FL 0.861), ‘Auditorium type seating’ (FL 0.829), ‘Comfortable chairs’ (FL 0.741), and ‘Number of screens available’ (FL 0.651). These items overall represent customer preferences for quality, amenities and ambiance.

- **Food and Hygiene (Restroom) Focused Customers**: We find there is high factor loadings for ‘Plentiful restrooms’ (FL 0.829), ‘Soft drinks and food’ (FL 0.787), and ‘Clean restrooms’ (FL 0.610). 


- **Gamer/ Arcade Customers**: We find the largest and only factor loading in factor 3 to be ‘Video arcade at the Movie Theatre’ (FL 0.954). 

Next, I conducted cluster analysis to create segments based on what people look for in a movie theater based on the regression factor scores for the three factors that we identified earlier. We used a K-means clustering technique with 99 iterations and a 3-cluster solution. The first cluster consisted of 52 individuals, the second one consisted of 94 individuals, and the third consisted of 294 individuals.

![image](https://github.com/user-attachments/assets/f011bacc-a246-4f99-85c9-96d154213870)

Next, I checked the 3-cluster solution against average scores for questions 5a to 5i and re-clustered the original clusters. This leads to more meaningfula nd interpretable clusters by simplifying and stabilizing the data. Finally, considering the 3 to 4 largest scores across the rows I have named the new clusters.

![image](https://github.com/user-attachments/assets/77b9e64e-0af2-4411-9331-6adfc30621e8)

My final clusters are:

- **Cluster1** - Quality Ambiance and Amenities Focused Customers: Looking at scores across the row for each cluster, I found that Cluster 1 focuses on those customers who select theatres that have a variety of amenities and quality ambiance. 

- **Cluster 2** – Seat and Restroom Focused Customers: Looking at cluster 2, we find that customers select theatres based on comfortable chairs and clean restrooms. 

- **Cluster3** – Wholistic Experience Focused Customers: Cluster 3 shows that customers select theatres based on having a variety of amenities and select a theatre than can provide them with wholistic experiences

Now to understand which segment of customers to target, I evaluated one behavioral variable and one financial variable against the 3 clusters using compare mean analysis method. As a financial variable, I chose “On average, about how many movies do you attend at a movie theater each month?” because the more movies a person sees, the more he is spending on movie tickets and as the behavioral variable, I chose “On average, about how many movies do you attend at a movie theater each month?” Comparing the means of the behavioral variable across the clusters I found that it is the highest for cluster 1. Next on comparing the means of the financial variable across the clusters, I found that there is a negligible difference between the highest mean and the second highest one. Ultimately, I chose the second highest mean which corresponds to cluster 1. Thus, I finally chose to target the Quality Ambiance and Amenities Focused Customers as they have the highest probability of spending it on movies and thus the best return on investment.

![image](https://github.com/user-attachments/assets/f1389a28-7c7c-4965-a0bf-5b87aff0b2eb)

Next, to make more effective marketing strategies, I have profiled the target segment (by taking cluster 1 as filter) in terms of information of movies playing at a movie theater, gender and age. 
The percentage of male students (42.3%) in cluster 1 is slightly higher than females (57.7%). In terms of age, students between ages 21-23 have the highest percentage at 34.6% followed by ages of 19-20 at 23.1%. Together, ages 19-23 make up 57.7%. Thus, we can consider males within the ages of 19- 23 as our target profile. 

![image](https://github.com/user-attachments/assets/a462d39c-ac2d-40c6-b022-73b76efa5305)

Finally, a Positioning Analysis is conducted using mean values of male and female students for gauging the importance of features in selecting a theater (Q5a – Q5i). This map visually shows how different amenities are perceived by gender.

![image](https://github.com/user-attachments/assets/3596733f-9f39-471d-9cbe-9e7726baa0c2)

The horizontal axis represents the preference for amenities by males, ranging from low preference on the left to high preference on the right. The vertical axis represents the preference by females, with low preference at the bottom and high preference at the top. Points on the map like Comfortable chairs, Quality of sound system, and Size of screen(s) are amenities that are highly preferred by males and have low preference among females (located near the top right corner). Clean restrooms, Number of restrooms available, and Auditorium type seating fall in the middle of the map, indicating neutral preferences across genders. Soft drinks and food are also in the center but slightly below, suggesting a balanced preference. Finally, video arcade is an amenity with low preference by both males and females (bottom left corner). Thus, we can infer that males seem to prioritize comfortable chairs, sound quality, and screen size, while females may not place as much emphasis on these factors. Clean restrooms and auditorium seating are universally appreciated, regardless of gender.

![image](https://github.com/user-attachments/assets/6cbb4b3a-455e-44e9-bdd4-59e609577d08)

## Managerial Implications


Based on the findings and the perceptual mapping, here are some managerial implications for targeting the male audience aged 19 to 23:

- **Feature Enhancement**:
  - **Comfortable Chairs**: Since males highly prioritize comfortable seating, consider investing in high-quality, ergonomic chairs. Comfortable seating can enhance the overall movie-watching experience and attract more male customers
  - **Quality of Sound Systems**: Focus on providing excellent sound quality. Upgrading audio systems or optimizing acoustics in the theater can significantly impact male satisfaction.
  - **Size of Screen(s)**: Larger screens tend to appeal to males. Ensure that your theater screens are appropriately sized to create an immersive cinematic experience.

- **Marketing and Promotion**:

    - **Targeted Campaigns**: Tailor marketing campaigns specifically to the 19-23 age group. Highlight the features they value most (e.g., comfortable seating, superior sound) in your advertisements.
    - **Social Media Engagement**: Engage with this audience on social media platforms. Share behind-the-scenes glimpses of your theater’s amenities, emphasizing the features that matter to them.
    - **Discounts and Special Offers**: Offer promotions or discounts during peak movie-going times for this demographic. Consider loyalty programs to encourage repeat visits.
    
- **Customer Experience**:

    - **Clean Restrooms**: While both genders appreciate clean restrooms, maintaining hygiene is crucial. Regular cleaning and well-stocked facilities contribute to a positive overall experience.
    - **Auditorium Seating**: Ensure that seating arrangements are comfortable and well-maintained. Consider premium seating options for an elevated experience
    - **Food and Beverage Option**s: Since soft drinks and food are neutral. preferences, explore diverse food offerings. Cater to different tastes and dietary preferences.

- **Feedback and Adaptation**:

    - Collect feedback from male customers regularly. Use surveys or comment cards to understand their preferences and areas for improvement.
    - Be agile in adapting to changing preferences. Monitor trends and adjust your offerings accordingly.

## Conclusion
In conclusion, targeting the male audience aged 19 to 23 should focus on enhancing features like comfortable chairs, sound quality, and screen size, while maintaining universally appreciated amenities such as clean restrooms and auditorium seating. However, these implications are specific to the target segment but maintaining a balance between gender-neutral amenities (like clean restrooms) and male-preferred features is essential for overall success. 

