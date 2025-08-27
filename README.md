# NLP ANALYSIS: SUSTAINABILITY SOCIAL MEDIA POSTS
Climate conservation is a key factor in today's world. The burning of fossil fuels, deforestation, industrial processes contribute to pollution, by emitting carbon dioxide and greenhouse gases. These gases blanket the earth, trap the sun's heat, which ead to global warming and climate change. In the long run weather patterns change and disrupt the usual balance of nature, which become harmful to the humans, plants and animals. Therefore, the need to conserve the environment through various ways. 

With the age of technology, specifically social media, it has been easier to sensitize on sustainability measures. Conversations are held around different social media platforms and even online campaigns run.

This project looks at social media posts, the topics discussed and performs EDA and predictive modeling.

## Data Understanding
This is obtained from [kaggle](https://www.kaggle.com/datasets/pratyushpuri/global-climate-action-social-media-trends-2024-25/data).  The data captures engagement metrics, user information, content themes, and calls to action from climate and environmental advocacy posts spanning from August 2024 to August 2025.

## Data cleaning
The data had zero missing values. Columns like `post_id`, `user_id`, `username` were dropped. New columns were created `post_month` and `post_year`. Text was cleaned for modeling.

## EDA
### Platform Distribution

<img width="571" height="501" alt="image" src="https://github.com/user-attachments/assets/aaa5230f-96d8-4426-9ce0-a77a5910f061" />

### User Locations

<img width="694" height="455" alt="image" src="https://github.com/user-attachments/assets/b901fd07-a8d2-4256-8f7d-efc5e0123efa" />

### Sentiment Distribution
<img width="640" height="504" alt="image" src="https://github.com/user-attachments/assets/431e2cc5-783c-433b-8311-f053136f37b8" />


### Climate Topics
<img width="722" height="455" alt="image" src="https://github.com/user-attachments/assets/656deb8d-b785-4cbb-b501-7b07da6cccb2" />


### Word Cloud
<img width="794" height="429" alt="image" src="https://github.com/user-attachments/assets/3c3e91cc-a8c3-4fe3-a88f-997fdd8a2eeb" />


## Modeling
<img width="691" height="471" alt="image" src="https://github.com/user-attachments/assets/ce775fa1-df63-4ca9-b60d-cecc2633eba4" />

## Conclusion
- There's a fair distribution of platforms used to post.
- Most users from the dataset come from Europe.
- Most of the posts have a positive sentiment, meaning they're in favour of sustainability.
- Eco-friendly materials is the most discussed topic. Could be the users are campaigning for materials which do not pollute the environment. There is a need for recyclable materials.
- The models performed poorly, with accuracies less than 50%. Therefore there needs to be more data to improve the models' accuracy.
