# Data-Science-Project
This project focused on building a model to predict whether the policyholder will  pay next premium on time or not.

### Motivation
Working on real data sets to predict some specific thing is really fun. Now, as you can imagine that in an Insurance company if a large number of
customers do not pay the premium on time, it might disrupt the cash flow and smooth operation for the company.
A customer may stop making regular premium payments for a variety of reasons - 
some may forget, some may find it expensive and not worth the value, some may not have money to pay the premium 
etc. In this case, building a model to predict whether a customer would make the premium payment can be extremely helpful for the 
company because it can then accordingly plan its communication strategy to reach out to those customers who are less 
likely to pay and convince them to continue making timely payment. 

### Abstract
Here our client is an Insurance company and they need help in building a model to predict whether the policyholder 
(customer) will pay next premium on time or not. An insurance policy is an arrangement by which a company 
undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the 
payment of a specified premium. A premium is a sum of money that you pay regularly to an insurance company for this 
guarantee.

### Process
Now, in order to predict whether the customer would pay the next premium or not, you have information about past 
premium payment history for the policyholders along with their demographics (age, monthly income, area type) and 
sourcing channel etc. Thus we were provided with real train and test data sets by Analytics Vidhya team.

<h4>Stages of Predictive Modelling</h4>
  <p>Here, I followed 5 major steps while building the model:</p>
  <li>Problem Definition</li>
   <li>Hypothesis generation</li>
    <li>Data Extraction / Collection</li>
     <li>Data Exploration and Transformation</li>
      <li>Model Deployment and Implementation</li><br>
      
 <p>In hypothesis generation we list down all the possible variables, which might influence problem objective and this should be done before looking at the data sets</p>
 
 <h4>Steps for Data Exploration</h4>
  <p align="center"<i><samp>Reading the data ---> Variable Identification ---> Univariate Analysis ---> Bivariate Analysis ---> Missing Value Treatment ---> Outliers Treatment ---> Variable Transformation</samp></i></p>
  
  <h4>Steps of Model Building</h4>
  <h5>☑️ Algorithm Selection</h5>
  <p>As in this problem our dependent variable is continuous therefore I used <i>LOGISTIC REGRESSION ALGORITHM.</i></p>
  <h5>🛠️ Training Model</h5>
  <p>Here we are supposed to learn relationship or correlation between independent & dependent variables.</p>
  <h5>📈 Prediction & Scoring</h5>
  <p>Now is the time to estimate and predict dependent variables of test data set by applying model rules.</p>
  
  ### Solution
  <p>After training the AUC-ROC score of provided data set came out to be <i>0.76 or 76%</i>.</p>
  
  ### Tools & Technologies
  <p>To build the model I have used: PYTHON , Statistics & Concepts of Machine Learning</p>
  <p>Libraries: Pandas, Matplotlib, scikit-learn</p>
  <p>Software: Jupyter</p>
  
  <i>** You can check the solution file in the code description.</i>
