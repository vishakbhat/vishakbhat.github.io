This is a repository of mini projects that I have worked on, during my college years as part of course curriculum and in later to learn something new. Each mini project typically perform a specific task and thus are intended to demonstrate functionality related to that task, unlike a full project which provides a full-fledged functionality (or multiples of these).

List of projects and their purpose:
1. Data Wrangling 01 [Wrangle_Job_listing.ipynb](../wrangling01/Wrangle_Job_listing.ipynb)
    Takes a (simulated) semi-structured text file of job listings, this project examines the structure involved and reformats the text into a structured data file of JSON and XML formats. This mini project illustrates:

    - Using Regex to examine a text file and identify phrases (or tokens) within the file and content associated with each token.
    - Building a vocabulary of tokens so that they can be standardised for better readability and computing.
    - Divide the text into "records" using predefined delimiters.
    - Construct structured data in the form of a dictionary from a stream of semi-structured text using these standarised tokens, including nested tokens.
    - Reformat dictionary into a JSON (containing lists and nested nodes) and XML; and save them to files. This simulates storing the data into persistent storage.
2. Data Wrangling 02 [Wrangle_property.ipynb](../wrangling02/Wrangle_property.ipynb)
    Takes 12 data files (across 7 categories of data) belonging to property listing and related data, and integrates them into one dataset which can be used to analyse property prises and its correlation to factors like property size, locality, features of the property (bedrooms, bathrooms, etc), distances to supermarkets / shopping centers / hospitals and commute time to CBD. This mini project illustrates:

    - Identifying issues with data and rectifying to get clean usable data.
    - Merging data based on common factors.
    - Spatial analysis of geo-location data and calculating distances between them.
    - Analyse data of train journeys and identify best route to a location while considering transfers (using 2 trains to reach a location with a stopover).
3. Data Analysis 01 [data_analysis01.pynb](../data_analysis01/data_analysis01.ipynb)
    Superconductivity is a phenomenon of exactly zero electrical resistance and expulsion of magnetic ﬂux ﬁelds occurring in certain materials, called superconductors, when cooled below a characteristic critical temperature. Superconductors are widely used in many industry ﬁelds, e.g. the Magnetic Resonance Imaging (MRI) in health care, electricity transportation in energy industry and magnetic separation, etc.
    Predicting the critical temperature (T c ) of a superconductor is still an open problem in the scientiﬁc community. In the past, simple empirical rules based on experiments have guided researchers in synthesizing superconducting materials for many years. Nowadays, features (or predictors) based on the superconductor’s elemental properties can be generated and used to predict Tc.
    This project analyses superconductor data from the Superconducting Material Database maintained by Japan’s National Institute for Materials Science (NIMS). The aim is to build statistical models that can predict T c based on the material’s chemical properties.
    - Analyse superconducting material dataset, identify important and correlated features.
    - Develop and compare models to predict critical temperature
    - Describe the models and justify choice of models
    - analyse and interpret results of critical temperate models
4. Data Analysis 02 [data_analysis02.pynb](../data_analysis02/data_analysis02.ipynb)
    Sentiment analysis also known as opinion mining is a subfield within Natural Language Processing (NLP) that build machine learning algorithms to classify a text according to the sentimental polarities of opinions it contains, e.g., positive or negative.
    In this data analysis project, we are interested in developing such an automatic sentiment classiﬁcation system that relies on machine learning techniques to learn from a large set of product reviews provided by Yelp. The levels of polarity of opinion we consider include strong negative, weak negative, neutral, weak positive, and strong positive. This project builds a sentiment classifier to assign product review to one of five rating levels using 50K labelled reviews and 600K unlabelled reviews.
    - Preprocess the data to generate tokens and numerical document representations which can be understood by ML models.
    - Create various models and evaluate the performance of the models on predicting the sentiment score. Identify the best model for the task.
