# Statistical-Programming-Assignment-2

Line 2-7: On these lines, the various different packages are imported
into R in order to allowed my joins, transformations and graphs to 
run.

Line 10-15: On these lines, the 5 Excel Spreadsheets; "advertiser", 
"campaigns", "impressions", "clicks" and "conversions" are imported
into R Studio.

Line 18-22: On these lines, the 5 tables that are listed above are 
converted from tables into tibbles(dataframe).

Line 25-40: On these lines, The "impressions", "conversions" and 
"clicks"are tallied. This is done as I believe that having the 
amount of "impressions", "conversions" or "clicks" is more 
important than having the time that they took place especially 
when using a small sample amount of data.

The variable names are then re-named in preparation to join 
all of the tables together in a future step. "id" in the 
"advertiser" is renamed to "advertiser_id" in order to join it 
with "advertiser_id" in the "campaign" table in a future step.

Line 44-47: On these lines, the tables are joined into one full
table. This is done by joining 2 tables together to create a new 
table. This new table is then joined with another table to create 
another new table. This process is repeated until all tables are 
joined into one "full_table".

Line 50-52: On these lines, 2 of the Variable names are changed in
"full_table" in order to make it more presentable.

Line 56-57: On these lines, The Campaigns are compared to their 
Budget using a bar chart to see which campaign is spending the most 
money e.g. Q4 Performance has a budget of 250,000.

Line 60-61: On these lines, The Campaigns are compared to the amount
of Impressions their adsets got using a bar chart e.g. Q4 Perfromace
got 10 impressions.

Line 64: On this line, We compare the Budget to Impressions of the 
Campaigns using a point plot. This helps us see how effective the 
campaign targerting was e.g. Q4 Performance had a budget of 250,000 
and only got 10 impressions whereas Run of Network had a budget of 
1000 and got 13 Impressions showing that their Campaign Targeting 
was way better.

Line 67-68: On these lines, the Campaigns are compared to the amount of
clicks their ads got using a bar chart e.g. Q4 Performance got 6 
clicks on their ads.

Line 71: On this line, We compare the Impressions to the Clicks using a
point plot. This helps us see how attractive the ad and the product is 
to the target audience e.g. Q4 Performance only got 10 Impressions but
6 clicks whereas Run of Network got 13 Impressions and only got 4 clicks.
This means that the people who Q4 Performance's ad reached were more 
interested in the ad than the people who Run of Network's ad reached.

Line 74-75: On these lines, We compare the Campaigns to the amount of
Conversions their ads got using a bar chart e.g. Q4 Performance got 3
conversions.

Line 78: On this line, We compare the Conversions to the amount of Clicks. 
This helps us see how effective the product/landing page is and if the 
pricing or other aspects of the product is attractive to the customer e.g.
Q4 Performance has a 50% Conversion Rate compared to Run of Network's 75%
Conversion Rate. This shows that Run of Network's Web page is more 
attractive to the customer that Q4 Performance's web page.
