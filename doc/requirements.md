### Story1. Register Seller

As a seller
I want to register
So that I can sell my things through the bid site.

AC1:
Given I provide my user name and password
When I register
Then I can register successfully.

AC2:
Given I provide my user name and password, which is less than 6 characters
When I register
Then I can NOT registered as a seller.