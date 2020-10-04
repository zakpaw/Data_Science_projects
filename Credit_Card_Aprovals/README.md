<p><b>Commercial banks</b> receive <u><b><em>a lot</em></b></u> of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. In this notebook, I will build an automatic credit card approval predictor using machine learning techniques, just like the real banks do.</p>
<p><img src="https://image.freepik.com/free-photo/hand-showing-credit-card-mock-up_23-2148304916.jpg" alt="Credit card being held in hand width="600" height="300"></p>

I'll use the <a href="http://archive.ics.uci.edu/ml/datasets/credit+approval">Credit Card Approval dataset</a> from the UCI Machine Learning Repository. The structure of this notebook is as follows:

<ul>
<li>First, I will start off by loading and viewing the dataset.</li>
<li>I will see that the dataset has a mixture of both numerical and non-numerical features, that it contains values from different ranges, plus that it contains a number of missing entries.</li>
<li>I will preprocess the dataset to ensure the machine learning model I choose can make good predictions.</li>
<li>After the data is in good shape, I will do some exploratory data analysis to build intuitions.</li>
<li>Finally, I will build a machine learning model that can predict if an individual's application for a credit card will be accepted.</li>
</ul>
