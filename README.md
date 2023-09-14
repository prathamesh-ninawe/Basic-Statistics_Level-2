

# Basic-Statistics_Level-2 SET 1

## 1)Look at the data given below. Plot the data, find the outliers and find out  μ,σ,σ^2

Name of company	Measure X
Allied Signal	24.23%
Bankers Trust	25.53%
General Mills	25.41%
ITT Industries	24.14%
J.P.Morgan & Co.	29.62%
Lehman Brothers	28.25%
Marriott	25.81%
MCI	24.39%
Merrill Lynch	40.26%
Microsoft	32.95%
Morgan Stanley	91.36%
Sun Microsystems	25.99%
Travelers	39.42%
US Airways	26.71%
Warner-Lambert	35.00%


## 2) Answer the following three questions based on the box-plot above.
(i)	What is inter-quartile range of this dataset? (please approximate the numbers) In one line, explain what this value implies.

	Here clearly 25 is the outlier
	Median = 71
	st quartile= 5
	2nd quartile = 12
	IQR = (12-5) = 7


(ii)	What can we say about the skewness of this dataset?

Positively skewed.


(iii)	If it was found that the data point with the value 25 is actually 2.5, how would the new box-plot be affected?

In that case there would have been no outliers, and it might have affected in the values of mean and median slightly. The boxplot might have moved towards right slightly.


## 3)  Answer the following three questions based on the histogram above.
(i)	Where would the mode of this dataset lie?

--- Between 5 – 8

(ii)	Comment on the skewness of the dataset.

--- It is positively skewed.
	
(iii)	Suppose that the above histogram and the box-plot in question 2 are plotted for the same dataset. Explain how these graphs complement each other in providing information about any dataset. 

--- By comparing both of them it is very clear that the data would be positively skewed. Also, would help us find the mean, and mode value.



## 4.	AT&T was running commercials in 1990 aimed at luring back customers who had switched to one of the other long-distance phone service providers. One such commercial shows a businessman trying to reach Phoenix and mistakenly getting Fiji, where a half-naked native on a beach responds incomprehensibly in Polynesian. When asked about this advertisement, AT&T admitted that the portrayed incident did not actually take place but added that this was an enactment of something that “could happen.” Suppose that one in 200 long-distance telephone calls is misdirected. What is the probability that at least one in five attempted telephone calls reaches the wrong number? (Assume independence of attempts.)

	If 1 in 200 long-distance telephone calls are getting misdirected.
probability of call misdirecting = 1/200
Probability of call not Misdirecting = 1-1/200 = 199/200
The probability for at least one in five attempted telephone calls reaches the wrong number
Number of Calls = 5
n = 5
p = 1/200
q = 199/200
P(x) = at least one in five attempted telephone calls reaches the wrong number
P(x) = ⁿCₓ pˣ qⁿ⁻ˣ
P(x) = (nCx) (p^x) (q^n-x) # nCr = n! / r! * (n - r)!
P(1) = (5C1) (1/200)^1 (199/200)^5-1
P(1) = 0.0245037




## 5.	Returns on a certain business venture, to the nearest $1,000, are known to follow the following probability distribution
x	P(x)
-2,000	0.1
-1,000	0.1
0	0.2
1000	0.2
2000	0.3
3000	0.1

(i)	What is the most likely monetary outcome of the business venture?


	As for 2000$ the probability is 0.3 which is maximum as compared to other


(ii)	Is the venture likely to be successful? Explain

	Yes its profitable
	p(x>0) + p(x>1000) + p(x>2000) + p(x=3000) = 0.2 + 0.2 + 0.3 + 0.1 = 0.8 
	this states that there is a good 80% chances for this venture to be making a profit
	
(iii)	What is the long-term average earning of business ventures of this kind? Explain

	The long-term average is Expected value = Sum (X * P(X)) = $800 which means on an average the returns will be +  $800

(iv)	What is the good measure of the risk involved in a venture of this kind? Compute this measure
 
The good measure of the risk involved in a venture of this kind depends on the Variability in the distribution. Higher Variance means more chances of risk
Var (X) = E(X^2) –(E(X))^2
= 2800000 – 800^2
= 2160000


# Basic-Statistics_Level-2 SET 2

## 1.	The time required for servicing transmissions is normally distributed with  = 45 minutes and  = 8 minutes. The service manager plans to have work begin on the transmission of a customer’s car 10 minutes after the car is dropped off and the customer is told that the car will be ready within 1 hour from drop-off. What is the probability that the service manager cannot meet his commitment? 

A.	0.3875   
B.	0.2676   
C.	0.5   
D.	0.6987 

 

## 2.	The current age (in years) of 400 clerical employees at an insurance claims processing center is normally distributed with mean  = 38 and Standard deviation  =6. For each statement below, please specify True/False. If false, briefly explain why.
A.	More employees at the processing center are older than 44 than between 38 and 44.
B.	A training program for employees under the age of 30 at the center would be expected to attract about 36 employees.

 


 


## 3.	If X1 ~ N(μ, σ2) and X2 ~ N(μ, σ2) are iid normal random variables, then what is the difference between 2 X1 and X1 + X2? Discuss both their distributions and parameters.       



## 4.	Let X ~ N(100, 202). Find two values, a and b, symmetric about the mean, such that the probability of the random variable taking a value between them is 0.99. 

A.	90.5, 105.9 
B.	80.2, 119.8 
C.	22, 78 
D.	48.5, 151.5 
E.	90.1, 109.9

 

## 5.	Consider a company that has two different divisions. The annual profits from the two divisions are independent and have distributions Profit1 ~ N(5, 32) and Profit2 ~ N(7, 42) respectively. Both the profits are in $ Million. Answer the following questions about the total profit of the company in Rupees. Assume that $1 = Rs. 45
A.	Specify a Rupee range (centered on the mean) such that it contains 95% probability for the annual profit of the company.
B.	Specify the 5th percentile of profit (in Rupees) for the company
C.	Which of the two divisions has a larger probability of making a loss in a given year?


# Basic-Statistics_Level-2 SET 3


## 1.	For each of the following statements, indicate whether it is True/False. If false, explain why.

I.	The sample size of the survey should at least be a fixed percentage of the population size in order to produce representative results.

False
The result depend upon the size of the sample. The sample size should have at least 30 observations.

II.	The sampling frame is a list of every item that appears in a survey sample, including those that did not respond to questions.

False
The sampling frame is a list of all the items in the target population from which the sample is selected

III.	Larger surveys convey a more accurate impression of the population than smaller surveys.

True
Large sample size will result in less std compared to small sample size. Thus larger sample is more accurate


## 2.	PC Magazine asked all of its readers to participate in a survey of their satisfaction with different brands of electronics. In the 2004 survey, which was included in an issue of the magazine that year, more than 9000 readers rated the products on a scale from 1 to 10. The magazine reported that the average rating assigned by 225 readers to a Kodak compact digital camera was 7.5. For this product, identify the following:

A.	The population - 9000
B.	The parameter of interest – Rating of camera 7.5
C.	The sampling frame – all readers of the issue where the survey was included
D.	The sample size - 225
E.	The sampling design
F.	Any potential sources of bias or other problems with the survey or sample – 
It is possible that only those who particularly pleased with the product participated in the survey which makes the result unreliable


## 3.	For each of the following statements, indicate whether it is True/False. If false, explain why.

I.	If the 95% confidence interval for the average purchase of customers at a department store is $50 to $110, then $100 is a plausible value for the population mean at this level of confidence.

True
Confidence interval indentifies the collection of values for the population parameter that are consistent with the sample.

II.	If the 95% confidence interval for the number of moviegoers who purchase concessions is 30% to 45%, this means that fewer than half of all moviegoers purchase concessions.

False
We have evident in that direction but we cannot confirm base on this data. Consider the range values.

III.	The 95% Confidence-Interval for μ only applies if the sample data are nearly normally distributed.

False
We should have large sample. The central limit theorm implies that the sampling distribution is normal regardless of the data itself.


## 4.	What are the chances that  ?

A.	¼ 
B.	½ 
C.	¾ 
D.	1

B

## 5.	In January 2005, a company that monitors Internet traffic (WebSideStory) reported that its sampling revealed that the Mozilla Firefox browser launched in 2004 had grabbed a 4.6% share of the market.

I.	If the sample were based on 2,000 users, could Microsoft conclude that Mozilla has a less than 5% share of the market?

II.	WebSideStory claims that its sample includes all the daily Internet users. If that’s the case, then can Microsoft conclude that Mozilla has a less than 5% share of the market?

 


## 6.	A book publisher monitors the size of shipments of its textbooks to university bookstores. For a sample of texts used at various schools, the 95% confidence interval for the size of the shipment was 250 ± 45 books. Which, if any, of the following interpretations of this interval are correct?

A.	All shipments are between 205 and 295 books.

B.	95% of shipments are between 205 and 295 books.

C.	The procedure that produced this interval generates ranges that hold the population mean for 95% of samples.

D.	If we get another sample, then we can be 95% sure that the mean of this second sample is between 205 and 295.

E.	We can be 95% confident that the range 160 to 340 holds the population mean.


Given:
the  % confidence interval for the size of the shipment was  books.
Find:
We have to find the which of the following interpretations of this interval are correct.
Solution:
Given that,
the  % confidence interval for the size of the shipment was   books.
=  
Option A is correct
The  % confidence interval for the size of shipment was books.
All shipments are not between   and   books. Because due to  % confidence interval for the size of shipment not all shipments.


## 7.	Which is shorter: a 95% z-interval or a 95% t-interval for μ if we know that σ =s?

A.	The z-interval is shorter
B.	The t-interval is shorter
C.	Both are equal
D.	We cannot say

The z-interval is shorter
because it tell us difference between mean of distribution and data points in standard deviation .


Questions 8 and 9 are based on the following: To prepare a report on the economy, analysts need to estimate the percentage of businesses that plan to hire additional employees in the next 60 days.

## 8.	How many randomly selected employers (minimum number) must we contact in order to guarantee a margin of error of no more than 4% (at 95% confidence)?

A.	600
B.	400
C.	550
D.	1000


600

## 9.	Suppose we want the above margin of error to be based on a 98% confidence level. What sample size (minimum) must we now use?

A.	1000
B.	757
C.	848
D.	543

# Basic-Statistics_Level-2 SET 4

## Q1)Examine the following normal Quantile plots carefully. Which of these plots indicates that the data …
Are nearly normal?   C
Have a bimodal distribution? (One way to recognize a bimodal shape is a “gap” in the spacing of adjacent data values.)  B and D
Are skewed (i.e. not symmetric) ?  A, B and D
Have outliers on both sides of the center? A and B

 


## Q2) For each of the following statements, indicate whether it is True/False. If false, explain why.

The manager of a warehouse monitors the volume of shipments made by the delivery team. The automated tracking system tracks every package as it moves through the facility. A sample of 25 packages is selected and weighed every day. Based on current contracts with customers, the weights should have μ = 22 lbs. and σ = 5 lbs.

Before using a normal model for the sampling distribution of the average package weights, the manager must confirm that weights of individual packages are normally distributed.

A sampling distribution is a probability distribution that represents the statistical outcomes of a specific sample statistic obtained from multiple samples drawn from a particular population. In our scenario, each sample consists of 25 packages, and there are numerous such samples, each comprising 25 different packages (25 packages in the first sample, 25 in the second, and so on). The mean weight for one of these samples is 22 pounds, with a standard deviation of 5 pounds. This implies that the individual package weights within each sample vary around the mean weight of 22 pounds, with fluctuations of up to ±5 pounds.

It's important to note that it may not be necessary to assume that the individual package weights follow a perfectly normal distribution before applying a normal model to the sampling distribution. The Sample Central Limit Theorem comes into play here. This theorem states that as the sample size becomes sufficiently large, the sampling distribution of the sample means will tend to follow a normal distribution, regardless of the distribution of individual package weights.

In summary, the key idea is that while individual package weights may not follow a normal distribution, when you aggregate these weights by taking the mean of each sample of 25 packages, the resulting sampling distribution of means will approach a normal distribution as the sample size grows. This property of the Sample Central Limit Theorem allows us to use normal distribution assumptions for making statistical inferences about the sample means, even when the underlying individual package weights may not be normally distributed.

The standard error of the daily average SE(x ̅) = 1.

As SE(Standard Error) = sample standard deviation / Square root of (number of sample) SE = 5 / (25)^1/2 SE = 1


## Q3) Auditors at a small community bank randomly sample 100 withdrawal transactions made during the week at an ATM machine located near the bank’s main branch. Over the past 2 years, the average withdrawal amount has been $50 with a standard deviation of $40. Since audit investigations are typically expensive, the auditors decide to not initiate further investigations if the mean transaction amount of the sample is between $45 and $55. What is the probability that in any given week, there will be an investigation?

1.25%
2.5%
10.55%
21.1%
50%

## Q4)The auditors from the above example would like to maintain the probability of investigation to 5%. Which of the following represents the minimum number transactions that they should sample if they do not want to change the thresholds of 45 and 55? Assume that the sample statistics remain unchanged.

144
150
196
250
Not enough information



## Q5) An educational startup that helps MBA aspirants write their essays is targeting individuals who have taken GMAT in 2012 and have expressed interest in applying to FT top 20 b-schools. There are 40000 such individuals with an average GMAT score of 720 and a standard deviation of 120. The scores are distributed between 650 and 790 with a very long and thin tail towards the higher end resulting in substantial skewness. Which of the following is likely to be true for randomly chosen samples of aspirants?

The standard deviation of the scores within any sample will be 120.
The standard deviation of the mean of across several samples will be 120.
The mean score in any sample will be 720.
The average of the mean across several samples will be 720.
The standard deviation of the mean across several samples will be 0.60


Standard error = sigma / (n)^0.5 = standard deviation / (sample size)^0.5 = 120 / (40000)^0.5 = 0.6

