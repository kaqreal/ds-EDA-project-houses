# <span style="color:green">__Data Science Bootcamp__

## <span style="color:black">__Project__: Exploratory Data Analysis with Python and SQL

---
## <span style="color:navy">__Context__

<span style="color:dark_grey">

Buying or selling a house is mostly an emotional decision that involves both personal experiences and good opportunities at the right time, but it has to be an informed decision to avoid losing money and headaches in the future. That's what this EDA project is all about, analyzing data to provide the best insights and recommendations for the stakeholders involved, both sellers and buyers, to guarantee their satisfaction at the end of the process. 

> ***"Buyers decide in the first eight seconds of seeing a home if they’re interested in buying it. Get out of your car, walk in their shoes and see what they see within the first eight seconds."*** – Barbara Corcoran (American businesswoman, Investor, Shark Tank personality, founder of The Corcoran Group - successful real estate brokerage in New York City)

Here I aim to put the clients' best interests first to maximize their investments, by providing the best cost-benefit balance and recommend them the best properties available in the market in the King County/Seattle - USA.

**Source:** King County Housing Data, containing information about home sales in King County (USA).

**Task:** 
* Choose a stakeholder from the list below
* Generate at least 3 insights regarding the overall data
* Provide at least 3 recommendations of houses for the chosen stakeholder
* Prepare a business presentation for the stakeholder

**Technical:**
* Prepare a Jupyter Notebook with the data processing and analysis for this project
* Provide a README.md file 
* Generate a requirements.txt file


## **EDA File**

Please take a look at the [EDA Project File](/Users/karine_real/Neue_Fische/ds-eda-project-houses/EDA.ipynb).

It contains all of the process that the data went through and the personalized recommendation for the chosen stakeholder: "Jennifer Montgomery" (High budget, wants to show off, timing within a month, waterfront, renovated, high grades year).

The data was extracted from a SQL database, was cleaned, adjusted, filtered, plotted and analysed. Some insights about the data were acquired and, finally, houses recommendations for the client were made.

There, it is possible to see how the data was treated, analysed and understood. It could also be used to do further analysis, personalize it to another client and so on.

## **Requirements**


This repo contains a requirements.txt file with a list of all the packages and dependencies you will need. Before you install the virtual environment, make sure to install postgresql if you haven't done it before.

```
brew update
brew install postgresql
```

In order to install the environment you can use the following commands:

```
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

See all requirements [here](/Users/karine_real/Neue_Fische/ds-eda-project-houses/requirements.txt)


Command to create a requirements file at the end of the project:

```
pip freeze > requirements.txt
```