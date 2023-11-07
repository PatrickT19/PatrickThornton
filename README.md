## Work Experience
### Data Analyst – _Partnerships; Marketing_
**Rocket Mortgage** | (_Jan 2020 - Aug. 2023_)
- Led and advised on several external partnerships and internal marketing campaigns. 
- Provided data and insights that informed the validity of continuing our business endeavors.
- Composed analyses using SQL, Salesforce, and Power BI to monitor and optimize existing processes.
- Stood up stored procedures used across the company to build new reporting in place of a data engineer.
- Resolved data and technology issues in our reporting systems.
- Deployed predictive models using AWS, SQL, and Python.
- Migrated MSSQL data warehouse tables to AWS.
- Managed projects to deploy partnerships with external partners. 
- Consulted partners on external calls, and to internal leadership.

### Operations Analyst
**Ally Bank** | (_May 2018 - Aug. 2018_)  
- Developed visuals using Python, ServiceNow, and Power BI to act as an incident dashboard for our key services and software.
- Coordinated incident recoveries through working with technology and business leadership.
- Tested applications by creating scripts to simulate user activity.
- Prepared raw data files to be adaptable in varying environments.

### Project Manager; GIS Information Technologist Assistant  
**Michigan State University** | (_May 2018 - Aug. 2018_)  
- Designed and maintained graphic representations of Geographic Information Systems (GIS).
- Liaison for Michigan State’s MISS DIG department and contractors regarding GIS/utility information around the campus of MSU.
- Assisted in resolving major crises on campus to mitigate risk to students and faculty as quickly as possible.


## Projects
### Song Genre Classification
[Project](https://github.com/PatrickT19/PatrickThornton/tree/d316f5c3fa911e11bc28bc1218ca528c95d4af15/Song%20Genre%20Classification)  
Explored the capabilities of differnt model types in capturing elements of a song including genre, lyrical topics, and emotions. To start we look at the differnt Scikit-Learn classifcation models trained on high level song features. These model types include Naive Bayes, Stocastic Gradient Descent, Logistic Regression, Support Vector Machine, Gradient Boost, and Random Forest. After arriving at our best model through feature engineering and hyper parameter tuning, we compare these models witha novel appraoch using nerual netrworks. For our neural network calssifier, we convertied Musical Instrument Digital Interface (MIDI) files into a heart matrix where x and y are the key and time stamp respectivly, and the intensity provides the color. From here we run a Convolutional neural network over the matrix to train the model for genre identification.

Running parallel to our supervised learning appraochins, we developed a semi-supervised, and a unsupervised model. The semi-supervised model aimed at classifying the emotions conveyed by a song's MIDI matrix. To do this we first had to assign emotions to songs which was done by using Google LLM Flan-T5 to identify emotions in a songs lyric set. One the songs were assigned emotions, we trained CNN on the MIDI matix. Topic detection was the last experiment conducted in this project. To identify topics, we tried an applied a Latent Dirichlet Allocation, and a Negative Matrix Factorization moedel to a set of word embeddings representing a songs lyric set.

### Visualizing Data Science in the Modern Day
[Project](https://github.com/PatrickT19/PatrickThornton/tree/d316f5c3fa911e11bc28bc1218ca528c95d4af15/Visualizing%20Data%20Science%20in%20the%20Modern%20Day)  
More representative of a data analytics report, this project focuses on showcasing data collection, cleaning, processing, and visualizng techniques in Python. Utilizing data on computer science related publications, this project tells a story about how universities and companies in differnt countries have been expanding their commitment to publishing papers on data science related topics. Digging deeper, we look at what model types and techniques these oragnizations have been focusing on over the past several years. Expanding the focus of the project, we look to the industry of data science has changed over time. This portion of the project uses data from an annual survey Kaggle puts out to professionals in the field. The survey has several reoccuring questions, but requried significant processing to be usable for an analysis. Once processed, the data was used to show how the industry of data science has grown globally over the last half decade, and what sort of skills professionals feel are the most important to be succesful in the field. Both of these topics are displayed visually through the use of several python packages including matplotlib, plotly, altair, geopandas, ipywidgets, and wordcloud.

### Forecasting Bike Sharing Trends
[Project](https://github.com/PatrickT19/patrickt.github.io/tree/0670814973ce45820ed15f8be838ec8701870ae3/Computational%20Mathematics%20Capstone)  


### Feature Recognition for Autonomous Vehicle Testing
- Employed TensorFlow’s software to train a deep learning model to recognize and annotate raw traffic video.
- Collaborated with team members and Aptiv employees.
- Presented work to Aptiv project managers and engineers.

### Multi-Model Basketball Analytics
[Project (PDF Only)](https://github.com/PatrickT19/PatrickThornton/tree/d316f5c3fa911e11bc28bc1218ca528c95d4af15/Multi%20Model%20Sports%20Analysis)  
- Trained in AWS EC2 Cluster to predicted outcome of NCAA basketball march madness games.
-	Methodically compared different model post hyper-parameter tuning and feature engineering. 

### Propensity to Close from Pre-Approval Letter
- Forecasted loan closings based on data available at approval letter to inform decisions on continuing partnerships.
- Created using data drawn from AWS and Python.

## Education
M.S., Applied Data Science | University of Michigan (_December 2023_)  
B.S., Computer Science | Michigan State University (_May 2019_)  
B.S., Computational Math | Michigan State University (_May 2019_)  
