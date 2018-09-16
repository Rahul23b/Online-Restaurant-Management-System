README File
In the home page of GameSpeed online shopping (index.html) website, click the link for Data Analytics on the left navigation bar. All text-based input is given in small-case letters and without any blank-spaces in-between the words. GameSpeed Retailer is assumed to have their shops in Chicago (Zipcode-60616), New York city (Zipcode-10016)  and California(Zipcode-94116). 
Collection used-“reviews1”
Database used: “gamespeed”

Features

1. Print the list of all products and their ratings
Select Return: All
Click on Find Data button.

2. Print a list of reviews where rating greater than 3
Select Return: All
Check Review Rating and enter the value as 3 
Enable Greater than option.
Click on Find Data button.

3. Get a list of products that got review rating 5 and price more than thousand.
  Select Return: All
 Check the Review Rating option and enter the value as 5 and enable “equals”.
Then check the Product Price option and enter the value as 1000 and enable greater than option.
 Click on Find Data button.

4. Print a list of how many reviews for every product.
Select Return: All.
Check the Group By option and select Product Name and click on the Find Data button, it will give the count of reviews for every product.

5. Get the list of reviews for shoppers in Chicago.
Select Return: All
Check the Retailer city option ,enter the value as chicago (in small-case letters) and see if “equals” is enabled.
Click the Find Data button.

6. Find highest price product reviewed/sold in every city.
Select Return : “Highest Price” (Also users can check for Lowest Price)
Check the Retailer City option and enter the city name as “chicago” (likewise for other cities) and enable “equals” option
Hit the “Find Data” button.

8. Get the top 5 list of liked products for every city
Select Return : “Top- 5 liked” .
Check the Retailer City option and enter the city name as “chicago” (likewise for other cities) and enable “equals” option
Hit the “Find Data” button.
The Top-5, Top-10 liked and disliked products are based on the sorting of “Review Rating “ for the products .

9. Print a list of reviews grouped by City.
Select Return : All
Check the Group by option and select the option “ city” from the dropdown menu displayed and click the Find Data button. To sort this grouped items either by ascending or descending order, we can select the option for sorting.

11. Get the total number of products reviewed and got Rating 5 in Every City
Select Return : All
Check the Review Rating option and enter the value as 5 and enable “equals”.
And then check the Group By option and select “city” from the drop-down menu and click on Find Data button .

12. Provide a Trending button that shows a list of most liked product in every city.
Trending button provides the list and count of products that is liked and sold/reviewed many times compared to the other products and grouping them based on city .This works based on the “Trending.java” file.

The data analytics page also lets the user to view the most disliked product , lowest price product ,top-10 products ,top-2 products in the “Returns” menu.

Group by can be mixed and matched with any filters from the above-mentioned review fields and can be sorted in ascending or descending order.

“SEARCH” field works with any type of input to match and it will fetch the related documents from the reviews1 collection.
			

	



