#Supermarket pricing



When you are checking out your shopping cart in a supermarket a lot of pricing decisions are made. In this exercise we are going to implement some of those pricing mechanisms.



- Implement a service where you can checkout a list of items. The items shouldn't be unique. This list represents the shopping cart scanning process so no initial grouping/sorting is allowed. The service returns the amount due.
  
- Some fruits and vegetables don't have a fixed price, but have a price per kg.
  
- Implement "buy 2 get one for free" this is only on the same item.
  
- Implement "X kg for X euro" pricing model. This means that if you buy X kg you will get a discount on it, but not on the complete weight.
  
- Implement large quantities discounts, where you receive a discount when you are buying multiple items of the same type. This can be buy 1 item for 5 euro 2 for 8 and 3 for 9.
  
- You can have multiple discounts at the same time.
  
- You should implement an decision log, printing out all the decisions made for the pricing.
  
- Add a coupon parameter to the method. Some of the coupons can be added with existing discounts other can't. Ensure that we get the best discount (coupon or existing discount).
