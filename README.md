<br />
<p align="center">
  <a href="https://github.com/rdmouhouadi/Mental_Health_State_Prediction">
  </a>

<h1 align="center">MHS-Pred</h1>

<p align="center">
    A Machine Learning based Webapp for predicting Mental Health State (mental illness)
    <br />
    <a href="https://github.com/rdmouhouadi/Mental_Health_Prediction"><strong>Explore the Project Report </strong></a> 
    ·
  <!-- will change the href=... to a link to the demo video-->
    <a href="https://github.com/rdmouhouadi/Mental_Health_Prediction">View the Demo</a>
    <br />
    <br />
    </p>
</p>


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
      </ul>
    </li>
    <li>
      <details open="open">
        <summary>
      <a href="#getting-started">Getting started</a>
        </summary>
      <ul>
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#utilization">Utilization</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contribution">Contribution</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#authors">Authors</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
    <li><a href="#references">References</a></li>
  </ol>
</details>

## **About The Project**

This is an ML group project completed as part of the mandatory Machine Learning with Python Labs Course at [DSTI](https://dsti.school/).

The data used for the project comes from the [NYS Office of Mental Health Patient Characteristics Survey 2019](https://catalog.data.gov/dataset/patient-characteristics-survey-pcs-2019). The data are organized by OMH Region‐specific (Region of Provider), program type, and by the following demographic characteristics of the clients served during the week of the survey: sex (Male, Female, and Unknown), Transgender (No, Not Transgender; Yes, Transgender and Unknown), age (below 17 (Child), 18 and above(Adult) and unknown age) and race (White only, Black Only, Multi‐racial, Other and Unknown race) and ethnicity (Non‐Hispanic, Hispanic, Client Did Not Answer and Unknown). Persons with Hispanic ethnicity are grouped as “Hispanic,” regardless of race or races reported.

## **Getting started**

### **Dependencies**
### **Installation**
To re-use this project, kindly refer to the following procedure:
1. Clone the repo
   ```sh
   git clone https://github.com/rdmouhouadi/Mental_Health_Prediction.git
   ```
2. Set up and activate a virtual environment
   
   * You can either use the actual virtual environment used for this project and provided in the       
      requirements.yml file
      ```sh
      conda env create -f requirements.yml
      ```

   * Set up and activate a virtual environment, then run
      ```sh
      pip install -r requirements.txt
      ```
## **Utilization**
The app follows a survey-like format: users answer a series of questions and receive a prediction of their mental health status based on their responses (see the [Demo Video](https://dstisas-my.sharepoint.com/:v:/g/personal/lina-marcela_diaz-bejarano_edu_dsti_institute/EbUOQuXJ13ZFor3UEmgxqpsBGFhY_CRZIAXAez_0uByI7A?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=WW1a8U)) These responses are stored anonymously in an SQLite database, which can be leveraged for future model retraining. 

## **Roadmap**
The model selected, the MLP, is used in a webapp for a user-friendly mean. The Webapp is built using Reflex. [Reflex](https://reflex.dev/docs/getting-started/introduction/).  is a Python framework that allows us to build both the front end and back end in Python. Unlike Streamlit, Reflex enables deeper customization through CSS and JavaScript-level configurations. Overall, the webapp is composed of 4 pages: the home page, the about page, the contact page and the assessment page. 

![Demo Screenshot](https://example.com/screenshot.png)

## **Contribution**
*We should decide if we invite and/or accept contributions to this project (leave it open source).*

## **License**
Distributed under the MIT License. See `MIT LICENSE` for more information.
## **Authors**
* Richie Mouhouadi - [@LinkedIn](https://www.linkedin.com/in/richie-mouhouadi) - [@Github](https://github.com/rdmouhouadi/)

* Linh Luong - [@LinkedIn](https://www.linkedin.com/in/linh-luong-69b651250) - [@Github](https://github.com/LinhLuong-2705)

* Lina Diaz Bejarano - [@LinkedIn](https://www.linkedin.com/in/lina-marcela-diaz-bejarano-0b71705a) - @Github

* Arigela Surendra [@LinkedIn](https://www.linkedin.com/in/arigela-surendra-564abb367) - @Github
## **Acknowledgements**
We would like to acknowledge:

* [Catia Silva](https://faculty.eng.ufl.edu/catia-silva/) as we used her README template file to make ours
## **References**
