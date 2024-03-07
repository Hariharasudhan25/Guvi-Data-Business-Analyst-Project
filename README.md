# Guvi-Data-Business-Analyst-Project
Guvi Data/Business Analyst . ECOMMERCE POWERBI DASHBAORD
Data understanding 


Columns

Title: Title of the product.
Id: Internal ID for the product.
actual_price: The actual price of the product.
average_rating: Average rating of the product.
brand: Brand of the product.
category: Category to which the product belongs.
crawled_at: Date and time the product information was
. collected.
description: Description of the product.
discount: Percentage discount applied to the product.
images: URLs of images associated with the product.
out_of_stock: Indicates whether the product is out of stock.
pid: Unique product identifier.
Product Details -The dataset comprises information on products available on the e￾commerce platform.
 It includes attributes such as product details,
pricing, seller information, and more
Seller - Name of seller
URL   - Product Link

Requirements 

User
1)This e-commerce product analysis project aims to providevaluable insights into the e-commerce landscape,
 benefiting bothbusinesses and consumers by informing strategic decisions andoptimizations.
2)Identifying popular product categories and brands.
3)Analyzing pricing trends and discount strategies.
4)Understanding seller behavior and performance.
5)Investigating customer preferences and product satisfaction.
6)Exploring correlations between various attributes such as price,rating, and brand.
7)Extract valuable insights from textual data using text analysistechniques, 
uncovering hidden trends and patterns in productdescriptions and details (Optional).

Solution

 * The Given data set is in JSON format.So,we get data through JSON format.
 * We load and Transform the JSON powerBI
 * We might do Data cleaning and Data processing in power query.
 * In power query we use first rw as header,remove the duplicate and rename the empty field as null.
 * we also extract the Product details before they are in list format ,we transform and extracted using
   split by delimiter
 * we analyze and took new measure for Total Sales
 * we also analyze and took only the right columns that need for futher requirements.
 
Reports

* We listed the Brands and Category in Slicer so that Customer as well as seller can easily findout report
  based on Brands and Category.
  
* We set the Card for Total Sales and Average rating for products.

* We find out popular brands and categories through the Total sales of the products.
  In X axis we place Brand and category also we filter only Top 10 based on Total sales that are 
  placed in Y axis for this we used (Stacked Column Chart).
  
* We also find out the over sales distribution of products through the sub categories.
  We used pie chart for this(Legend - Sub categories, values - Total Sales)
  
* We used Card for to know the Title of the product(product name).

* we also find out price distribution and discount strategies based on  Avg selling,actual price 
  by category and discount. For this we used area chart (X axis - category,discount ,
  y axis - Avg sell price , secondary Y axis - Avg actual price)
  
* count the product id based on selling in that we can know about product price over the crawl date.

* seller performance based on product sold,rating by brand wise for this we used table chart.
  list of items we used for table charts are ( columns - seller,count of pid, avg rating,brand)
  
* Customer preference based on product details,rating,discount for this we used table so that user 
  can easy able to view (columns - category,brand,average_rating,fabric,patterns,colors etc.
  
* Apart for this used the report formatting and doing dashboard much easier and looks Cleany.


                                                    Thanks & Regards,
												                         Hariharasudhan 86678 69920.
                                    portfolio - https://sites.google.com/view/hariharasudhan-s/home
