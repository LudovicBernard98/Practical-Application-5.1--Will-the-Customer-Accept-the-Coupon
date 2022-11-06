# Practical Application 5.1: Will the Customer Accept the Coupon
# This is a practical assignment 5.1 exploring various visualizations of a large categorical dataset.

Will a Customer Accept the Coupon?

While driving around you receive a coupon on your cellphone for a restaurant, a coffee or a bar. Would you accept such a coupon? What are the variables that could impact your level of acceptance? Are you more likely to accept certain types of coupons? Does the Weather impact your decision? Using the data provided by the UCI Machine Learning repository and collected via a survey on Amazon Mechanical Turk, I will explore such relationship.

Summary of Findings:

After the initial cleaning of the data, I carried out analysis to answer specific questions. Most importantly I focused on the Bar coupons and Coffee House coupons. See jupyter notebook: "https://github.com/LudovicBernard98/Practical-Application-5.1--Will-the-Customer-Accept-the-Coupon/blob/main/prompt.ipynb" to have access to the code. 

A challenge I encountered which I realized when pushing the notebook in Github is that plotly graph do not show in a notebook. I tried many potential solutions without success. Spending a lot of time, exploring solutions, I was not able to appropriatly address the issue. For this reason, I have provided a PDF file which should be consulted in parallel showing the various visualizations I used. PDF with Graph: https://github.com/LudovicBernard98/Practical-Application-5.1--Will-the-Customer-Accept-the-Coupon/blob/main/prompt.graph.show.pdf
This was an important learning curve with many hours spent trying to maintain the integrity of my work. Next GitHub assignment, I will focus on other Python packages which will remedy such problems.

Here are the main attributes I found to be significant.

1. The more a person visits a bar or a coffee house the more likely they are to accept a coupon for such location. 
2. Given people visited a bar more than once a month, people older than 25 were 66% likely to accept a coupon in comparison to the rest of data which accepted 37% of the coupons offered.
3. People with passengers that visited the bar more than once a month were almost twice as more likely to accept a coupon with 71.4% acceptance rate than the rest of bar dataset.
4. Coffee House acceptance was much higher for  the hours of 10AM and 2PM. Hence, time of day is has an important impact of coffee house coupon acceptance.
5. A sunny and hot day, increase the likelyhood of people accepting a Coffee House coupon.
6. The same direction of the coupon offered had an marginal impact on the acceptance rate of coffee house coupons.

