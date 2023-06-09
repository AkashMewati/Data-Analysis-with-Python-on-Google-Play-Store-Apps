# Data-Analysis-with-Python-on-Google-Play-Store-Apps

## Tasks
### 1. Data clean up – Missing value treatment
#### a. Drop records where rating is missing since rating is our target/study variable

#### b. Check the null values for the Android Ver column.
i. Are all 3 records having the same problem?
ii. Drop the 3rd record i.e. record for “Life Made WIFI …”
iii. Replace remaining missing values with the mode

#### c. Current ver – replace with most common value

### 2. Data clean up – correcting the data types
#### a. Which all variables need to be brought to numeric types?
#### b. Price variable – remove $ sign and convert to float
#### c. Installs – remove ‘,’ and ‘+’ sign, convert to integer
#### d. Convert all other identified columns to numeric

### 3. Sanity checks – check for the following and handle accordingly
#### a. Avg. rating should be between 1 and 5, as only these values are allowed on the play
store.
i. Are there any such records? Drop if so.

#### b. Reviews should not be more than installs as only those who installed can review the
app.
i. Are there any such records? Drop if so.

### 4. Identify and handle outliers –
##### a. Price column
i. Make suitable plot to identify outliers in price
ii. Do you expect apps on the play store to cost $200? Check out these cases
iii. After dropping the useless records, make the suitable plot again to identify
outliers
iv. Limit data to records with price < $30
#### b. Reviews column
i. Make suitable plot
ii. Limit data to apps with < 1 Million reviews
#### c. Installs
i. What is the 95th percentile of the installs?
ii. Drop records having a value more than the 95th percentile
Data analysis to answer business questions


### 5. What is the distribution of ratings like? (use Seaborn) More skewed towards higher/lower
values?
#### a. How do you explain this?
#### b. What is the implication of this on your analysis?

### 6. What are the top Content Rating values?
#### a. Are there any values with very few records?
#### b. If yes, drop those as they won’t help in the analysis

### 7. Effect of size on rating
#### a. Make a joinplot to understand the effect of size on rating
#### b. Do you see any patterns?
#### c. How do you explain the pattern?

### 8. Effect of price on rating
#### a. Make a jointplot (with regression line)
#### b. What pattern do you see?
#### c. How do you explain the pattern?
#### d. Replot the data, this time with only records with price > 0
#### e. Does the pattern change?
#### f. What is your overall inference on the effect of price on the 

### 9. Look at all the numeric interactions together –
#### a. Make a pairplort with the colulmns - 'Reviews', 'Size', 'Rating', 'Price'

### 10. Rating vs. content rating
#### a. Make a bar plot displaying the rating for each content rating


# After Analysis we have came to the below findings which are:-
1) Most of the ratings of apps are between 3 to 5
2) there is correlation between Size and Rating 
3) we can say that there is negative correlation between Price and Rating





