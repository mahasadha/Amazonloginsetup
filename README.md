# Amazonloginsetup

Consider the following Feature File and Apply BDD Test
Feature: As a Amazon user I should be able to login and logout with valid credentials
Scenario: Login into the application with valid credentials
1.	Given I am on the Login page URL "https://www.amazon.in/"
2.	Then I click on sign in button and wait for sign in page
3.	When I enter username as "testusername"
4.	And I Click on Continue button
5.	And I enter password as "testpassword"
6.	And click on login button
7.	Then I am logged in
8.	And I clear cart items if any
9.	Then I choose Electronincs>Headphones and headphones list out
10.	Then I add first availabe headphone to cart
11.	Then I search "Macbook pro" and add second available item to cart
12.	Then I Select cart from home and remove the earlier added headphones
13.	Then I Reduce the Quantity of the macbook pro product to one and proceed to checkout
14.	And I Click on Sign out
15.	Then I got log out from the application and land on sign in page
