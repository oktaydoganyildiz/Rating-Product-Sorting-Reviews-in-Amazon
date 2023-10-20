# Rating-Product-Sorting-Reviews-in-Amazon


![image](https://github.com/oktaydoganyildiz/Rating-Product-Sorting-Reviews-in-Amazon/assets/70387935/dde4403e-2878-4c6e-880b-c8feb5e7fb65)


# Business Problem 👩‍💻
One of the most important problems in e-commerce is the correct calculation of the points given to products after sales. The solution to this problem means providing more customer satisfaction for the e-commerce site, making the product stand out for sellers, and a smooth shopping experience for buyers. Another problem is the correct ordering of the comments given to the products. Highlighting misleading comments will directly affect the sales of the product, causing both financial and customer loss. By solving these 2 basic problems, e-commerce sites and sellers will increase their sales, while customers will complete their purchasing journey without any problems.

As a maintainer of an online community, which is having a lot of products where user gives a rating to products based on their experience, then it is definite that at some point you have to find an answer to questions like, how you are going to show the product on the page based on filters i.e. like highest voted or lowest voted, etc.? Or How can you rate a product based on upvotes and downvotes? How you can give a score to a product which is rated on a K scale by users?

# The Goal of the Project 🎯
Try to calculate product ratings more accurately and to sort product comments more accurately with Wilson Lower bound Score Approximation


![image](https://github.com/oktaydoganyildiz/Rating-Product-Sorting-Reviews-in-Amazon/assets/70387935/8128949a-f954-4e7b-9c03-e233b9ce6cb1)

The idea here is to treat the existing set of user ratings as a statistical sampling of a hypothetical set of user ratings from all users and then use this score. In other words, what user community would think about upvoting a product with 95% confidence given that we have an existing rating for this product with a sample (subset from the whole community) user ratings.

Therefore if we know what a sample population thinks i.e. user reviews for a product, you can use this to estimate the preferences of the whole community.
