# FDA_practice
Practice for course "Fundamental of Data Analytics"

Dataset : https://drive.google.com/file/d/1JUM5y1o4hYdZIioy2gN-I22a8673S6Pt/view?usp=sharing

<br>
<br>
<br>

# FDA Course Homework

- **For this homework, please use the first 10000 rows**
- `pd_data = pd_data[:10000]`

## 1. Top-10 Reviewer

- Sort by number of reviews (hint : "ProfileName", "UserId")
- Also, show his/her average score

## Desired output
![](https://i.imgur.com/pBg5fLo.png)
![](https://i.imgur.com/y1e5Vj3.png)

## 2. Plot score distribution for the user with the most number of reviews

## Desired output
![](https://i.imgur.com/5A4YTU2.png)

## 3. Plot pandas Series DataFrame (Time->Date)

- axis-X : Date of reviews (transfer column "Time" -> Date)
- axis-Y : Numbers of reviews in the date interval
- Type : bar graph

## Desired output
![](https://i.imgur.com/kRmLLRK.png)

## 4. Plot HeatMap using seaborn 

- Correlation between numeric features (Id, HelpfulnessNumerator, HelpfulnessDenominator, Score, Time)

## Desired output
![](https://i.imgur.com/4gh1Cem.png)


## 5. Helpful percent

- If viewers of that comment upvote the comment, then it adds to Helpfulness numerator.
- If viewers of that comment just make a comment, then it adds to Helpfulness denominator.
- **Note : you should filter out some cases with numerator > denominator**
- Plot the distribution of helpful percent (hint: .hist())

- **Ratio = -1, if both Helpfulness numerator & Helpfulness denominator are zero.**


## Desired output
![](https://i.imgur.com/oHSEX8W.png)
