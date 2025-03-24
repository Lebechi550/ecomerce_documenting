I started by first doing a little cleaning on the column for Purchase_Amount by changing the data type after I have removed the $ sign. 
I calculated the sum of Purchase_Amount using =sum(J:J)
I then added another column (Age_Group) to the existing ones
I grouped the age into young and old using =IF(b2 <=35, "Young", "Old")
I calculated the number of customers using countif on Customer_ID
I also compared the number of customers  who used discount with those who didn't
