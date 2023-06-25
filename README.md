# Recommendation-Engine
A recommendation engine is a type of data filtering tool using machine learning algorithms to recommend the most relevant items to a particular user or customer. It operates on the principle of finding patterns in consumer behavior data, which can be collected implicitly or explicitly.


**1. Content-based filtering**
Content-based filtering is based on a single user’s interactions and preference. Recommendations are based on the metadata collected from a user’s history and interactions. For example, recommendations will be based on looking at established patterns in a user’s choice or behaviours. Returning information such as products or services will relate to your likes or views. With an approach like this, the more information that the user provides, the higher the accuracy.

Given the privacy and regulatory issues are important in some industries’ services, personal metadata and individual transactional data can be missing at the outset. These issues are commonly known as ‘cold start’ problems for recommender systems using this approach. Cold start occurs when a recommender system cannot draw inferences for a query due to lack of sufficient information. A particular form of the content-based recommendation system is a case-based recommender. These evaluate items’ similarities and have been extensively deployed in e-commerce.

A recommendation like ‘products similar to this’, is a typical instance of this type of approach. Overall, these are limited though to the specific domain and the level of categorisation available.

**2. Collaborative filtering**
Collaborative filtering is another commonly used technique. Collaborative filtering casts a much wider net, collecting information from the interactions from many other users to derive suggestions for you. This approach makes recommendations based on other users with similar tastes or situations. For example, by using their opinion and actions to recommend items to you or to identify how one product may go well with another. ‘Next buy’ recommendations is a typical usage. Collaborative filtering method usually has higher accuracy than content-based filtering; however, they can also introduce some increased variability and sometimes less interpretable results. They are especially weak in the absence of previously collected data. Without meaningful information on others, it becomes harder, naturally, to participate in any single person actions.

Build better voice apps. Get more articles & interviews from voice technology experts at voicetechpodcast.com

**3. Knowledge-based system**
Knowledge-based systems are systems where suggestions are based on an influence about a user’s needs and based on a degree of domain expertise and knowledge. Rules are defined that set context for each recommendation. This, for example, could be criteria that define when a specific financial product, like a trust, would be beneficial to the user. These do not, by default, have to use interaction history of a user in the same way as the content-based approach is, but can include these as well as customer products and service attributes, as well as other expert information. Given the way the system is built up, the recommendations can be easily explained. But building up this type of framework can be expensive. It tends to be better suited to complex domains where items are infrequently purchased or hence, data is lacking. Given this, it doesn’t suffer the same cold-start up problems as others above.
