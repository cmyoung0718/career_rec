# Career Recommendation Engine

The goal of this project was to build a job recommendation engine. With vectorized skills as the features, the job titles were first clustered using hierarchical clustering. These clusters loosely represent industries. When a new user's resume comes in, they are assigned a cluster (multinomial logistic regression) and recommended job titles from each cluster using cosine similarity, as well as five skills the new user lacks that they need to obtain to get that position.

Parts of the code have been purposely left out for legal reasons.

### Slide deck

{::nomarkdown}
<iframe src="https://docs.google.com/presentation/d/1WVKsxtuPchFBn5foV0bCIa-f6DKy-i_-7MDue69OedU/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
{:/}