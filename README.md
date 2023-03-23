
# CSE 291 Antisocial Computing Filter Bubble Final Project

Project Members:
* Chinmay Rane
* Shivam Chawla
* Manasi Agrawal
* Yash Khandelwal

Dataset: https://www.kaggle.com/datasets/gspmoreira/articles-sharing-reading-from-cit-deskdrop?resource=download

 	
## Motivation
Social media platforms use recommender systems to provide personalized results to users based on their interests, interactions, and choices. However, these algorithms can create "Filter Bubbles" where users are only exposed to familiar content, leading to limited information and potential radicalization. This can be caused by the echo chamber effect where users are only exposed to content that aligns with their preferences, potentially leading to the spread of false or harmful information.\
To prevent Filter Bubbles, it's important to expose people to alternative ideas and beliefs. One way to achieve this is to present a neutral view by disregarding the user's current history and preferences, allowing them to view content from all perspectives. This can be done by recommending content that the user's friends/connections have interacted with and that don't align with the user's views, and by connecting the user with such friends to encourage discussion and debate.\
Prior work suggests that designing a system/widget to connect users and encourage discussion/debate can be achieved by designing systems that encourage respectful communication, provide a diverse range of perspectives, and prioritize accurate information. To avoid reducing user engagement, it is important to provide clear incentives for participation, limit the amount of content, and ensure that content is easy to access and understand. Additionally, prior work suggests that it is important to address potential biases and ensure that users are exposed to a range of viewpoints, not just those that align with their existing beliefs.\
## Implementation
We built two types of recommender systems to eliminate filter bubbles:
### Type 1
The recommender system does not consider the user's profile or past engagement. Instead, it recommends content based on external factors such as source credibility, opinion diversity, and content engagement. These factors are independent of the user and aim to increase user engagement with diverse types of content.
### Type 2
This recommender system combines content-based and collaborative filtering algorithms to provide users with diverse content based on their profile, social network, and content their connections interact with. It aims to increase user engagement, reduce echo chambers, and constantly improve recommendations using latent factor models and user feedback. 
## Browser Extension
This system is implemented as a browser extension and can be integrated with various social media platforms as well as news platforms. The extension will be designed to allow users to switch between their regular feed and the opposing feed.
## Conclusion
By exposing the user to different perspectives and views, this recommender system is capable of reducing the prevalence of filter bubbles and preventing radicalization. This will reduce polarization and increase critical thinking in the social media world.
 
## Acknowledgements:
* Prof. Kristen Vaccaro (Instructor)
* Hayden McTavish (TA)
* Sanjana Balamurugan (TA)

