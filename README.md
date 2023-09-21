# e-commerce-backend-restful
## Project Description 
I want to implement in e-commerce with djangorestframework and I want to use [DjangoStyleGuide](https://github.com/HackSoftware/Django-Styleguide#how-to-ask-a-question-or-propose-something) for this project to implement it cleaner let me explain it briefly for you the most important concepts is this<br> 
**bussiness logic should live in services selectors model properties and model clean method for additional validations.**<br>
**bussiness logic should not live in API and Views , Serializers , CustomManagers or Queryset and signals**

## Projects Sections
### user
In this project we have  types of users admin and customer and In addition I should say that I don't want to use **Abstract Model** instead of that  I want to use **AbstractBaseUser**.
this section incluse login , register , forgetpassword/resetpassword  username going to be phonenumber and after regist must we'll send otp to verify the phonenumber.
for authentication I will use JWT that contans freshtoken and accesstoken
### Product Section
Product is the most important section of the project for this model we have **sulg** that must be unique  and **feautres of products** we must implement this section the best way the we can do it  because we also have another feature to compare to porduct and others fields .
1. for each product we must have color and materials that each color or material can have different price 
1. an other important feature is that user can add insurance and guarantee(for example 3 month or 6 month) for some specific products.<br>
1. fitler for products <br>
1. search for product with slug and description of that products<br>
1. category for product this feature must contains tree category and also list of product of each category<br>
1. customer can save the product in his/her account for next shopping 
1. history of the orders
1. tracking code for orders
1. order status
1. send sumit order report for manager (sms /telegram /etc....)
1. if a product doesn't exists user can active sth to send email/sms when product exists 
1. add discount code for order
1. basket for product list
### Admin
1. list of submited orders
1. able to CRUD for Product
1. able to CRUD for Category
1. generate discount code for list of users or specific user.
1. ten basic manager report for product that contains date range filter and etc
1. ten basic manger report for customers that contains date range filter and etc
## Technologies
1. Django
1. DjangoRestFrameWork
1. Docker
1. Nginx
1. JWT 
1. PostgreSql
1. pytest
1. UnitTest
1. CI/CD (Github actions)
