# Database-project-1

* Project Component 1 Description:  
LoyaltyFirst Inc. is a music store that needs to develop a customer loyalty program supported by an Oracle database backend. The customer loyalty program also known as a "frequent customer" program identifies LoyaltyFirst customers as valued members through a card that accumulates loyalty points whenever they buy items from the LoyaltyFirst store.   
LoyaltyFirst Inc. is lucky enough to contact you and ask you to develop the database system that supports their loyalty program. A crude description of the business rules and operations is provided below. 
this information might not be comprehensive or complete and sometimes you need, as a designer, to get back to LoyaltyFirst Inc. (the GTAs and Professor will play the role of LoyaltyFirst Inc.) to get more details to help you deliver a complete database design.  
The process starts with the customer buying an affiliation kit that includes the loyalty card. The customer should fill some personal data such as: **the Social Security Number, full name, family data, mailing address, and other demographic information such as age (date of birth), sex, marital status, occupation, etc.** If the customer loses their card or if it is damaged due to use, they must buy a new one. Another card is issued with a different ID, but it remains linked to the same customer.   
The objective of the program is to foster customer loyalty towards attracting new customers, performing marketing analysis and sending promotions to specific market segments. This can be done through historical information of purchases associated with the customers personal and demographic data.  
When the customers buy at one of the LoyaltyFirst stores, they are asked: do you have a frequent customer card? If so, the card is swiped through a reader or POS (point of sale) in which the card number is linked to the transaction or details of purchase that the customer makes in the store.  
**Note that LoyaltyFirst Inc. has 6 store branches, and this number might expand in the coming years.**    
The customers are "rewarded" with each purchase by accumulating points, the accumulation rules may vary with each product: **40 points for a Fender Stratocaster guitar, 35 points for a Yamaha P 125 Piano, 3 points for a music CD, …**  
LoyaltyFirst Inc. provides special promotions of **double or triple points on special dates** or occasions in selected store branches. Upon reaching a certain number of accumulated points, the customer can redeem them for items within other establishments known as **“Exchange Centers”**. In other words, there are prize tables, for example: trip to Cancun 10,000 points, microwave oven 2600 points, …  
In order for the customer to have faster access to the prizes, "family accumulation groups" are allowed in which the purchase points of any member of **the family results in 30% of the points going to the card of the other family members**. For example, if the customer Bob makes a purchase that results in 250 points, 75 points go to the cards of Jane, Sam, and Rebecca (Bob, Jane, Sam, and Rebecca are members of the same family).  
**To simplify the program, LoyaltyFirst Inc. decided that the points will have an indefinite duration and will not expire.**  
Develop the conceptual ER model of the database to support the above business rules and operations. You should be able to identify the necessary entity sets, their attributes, and the corresponding relationships among them. **Obviously, entities such as Customers, Cards, Transactions, Products, Branches, Redemption_History, Prizes, Offers, Families, etc**. should be part of the database. **10 to 20 entity sets** would be a logical number for such a system. You should provide drafts of your ER diagram from the moment you scratch the first ER design to the point where you reach the final design to be submitted. I would expect to see at least 5 drafts to reach a final design. Drafts could be scratched by pencil on a paper and scanned, however, the final ER design should be drawn using a computer tool.  If you believe that some information is missing or that some business rules can be enhanced, suggest additional assumptions and briefly explain their rationale in a supporting Word document to be provided with the final ER diagram and ER drafts in the submitted ZIP file.  
Summary of the contents to be included in the submission ZIP file:  
* 1-	At least 5 drafts of the ER diagram (can be scratched on a paper and scanned) showing how you progressed towards the final ER design.  
* 2-	The final ER design drawn using a computer tool of your choice.  
* 3-	A supporting Word document justifying any assumptions you made or added on the described business rules. Any comments documenting your experience from the first design draft to the final ER diagram should be included in the supporting Word document.  
