<h1 align="center">PyBay 2024</h1>

![PyBay](link here)

## Description:
Collection of information from [PyBay 2024](https://pybay.org/) courtesy of [Hackbright Coding Academy Alumni Resources](https://hackbrightacademy.com/). Python Developers gathering to gether sharing information in regards to the Python Developer Community in the San Francisco, CA area. 

## Technology Stack
- **Frontend/Client:** React.js, HTML5, CSS, framework, etc.
- **API:** api calls or external sources used
- **Backend/Server:** node.js/express or python alternatives, include databases

## Screen Shots:
<p align="center">Please reference the screenshot folder for more available images</p>

`selected image 1`

`selected image 2`

`selected image 3`

## Run Code (Environment)

### Front-End Instructions `<examples below>`
- confirm that config is appropriate:
```
> node -v
> npm -v
> git --version
```

- Initial package.json & install dependenies(localhost:3000):
    - Must be `cd`'d into frontend/client for install
    - MUI, `react-router-dom`, redux, formik, etc... (see resources)
```
> npx create-react-app <project name>
> cd <project name>
> npm install @mui/icons-material @mui/material @emotion/styled @emotion/react
> npm install --save react-router-dom
> npm install react-redux @reduxjs/toolkit
> npm install formik yup dotenv react-responsive-carousel
> npm install --save @stripe/react-stripe-js @stripe/stripe-js
```
- Test front-end once pages are generated (ctrl-c to exit):
```
> npm run start
```

### Back-End Helpful Instructions `<examples below>`
- Initial package.json & install dependencies:
    - Must be `cd`'d into backend/server for install
```
> npx create-strapi-app@latest <project name>
> cd <project name>
> npm install --save stripe
```
- Strapi Database generated (ctrl-c to exit):
```
> npm run develop
```
- **Avoid** *npm run start* and use the `npm run develop`. 
- Allow server to restart with each edit (see resources): 
    - **Content-Type Builder**: Item entry
    - **Media Library**: upload photos
    - **Permissions**: Settings > Roles > Public 
- In frontend fetch `item` from backend (*localhost:1337*):
```
const grouping = "items"
const items = await fetch(
`http://localhost:1337/api/${grouping}`
)
```
--------------------------
### Deployment

--------------------------
## Resources `<examples below>`

- Sponsors:
    - [Intuit]()
    - [neo4j](), [Auth0 by Okta]()
    - [Python]()
      
- `Tech used and links associated`

`<examples below>`
- **PostMan** for API Tests [here](https://www.postman.com/)
    - jsonwebtoken / [jwt](https://jwt.io/) for Authentification & install [here](https://www.npmjs.com/package/jsonwebtoken)
    - jwt Debugger [here](https://jwt.io/#debugger-io)
- [bcrypt.js](https://www.npmjs.com/package/bcryptjs) part of password hasing for user Authentification. 


#### **style:** 
- `frameworks and links associated`

- Filler Text [typographic](https://generator.lorem-ipsum.info/)
    - Lorem Ipsum 
- Google Fonts [here](https://fonts.google.com/)

#### **helpful hint:** 
- `useful hints for future projects to go faster`
- console log testing with `ctr-alt-l` 
- Always Stay Positive & Triple Check Permissions :)


<!-- 
### TODO stx: 
Future Structure (stx):

--> 
<h3>Pamela Fox: Improve with Python </h3>
https://pamelafox.github.io/improv-with-python/

- Improve with Python... fun, interactive talk using language models.

<h3>Data Science: Apache Arrow, Pandas and Parquet</h3>
Datasources -> Data Collection -> Data storage & Transofrmation
Telegraf open source injection agents is great agent? Influx or ParK files or "output plug ins": Look at the slide deck in file... 
SQl Aggregatoin fx  - DB3.0 Apache Data Query Engineer noSQL using SQL language? Google Later? 
Telegraf? Dispatched Q and stream the data? 
PyArrow - python version of Apache Arrow for the data format transfer...
Apache Parquet - look into...
Apache Arrow - data analytics and tooling and basics, standard... columnar data format - CPU and GPU architecture? 
Flight (arrow) vs Flight SQL (superset: ORM's UI builders)
- Looking at NOAA for jupiter notebook that can be examined for changes overtime...output only, not the input or inducing factors...
   Prophet - weather forestcasting (combines seasons, holidays, etc..) Time series pitfalls... look up later
Solution: Apache Arrow allows data transfer with ease (centralized system to plug into other databases)

<h3>Data Science: Raising Python Quality in AI orgs</h3>
- AI driven expert platform - look at raw slide deck at EoD
    - AI vs Quantum Computering
    - Open Source vs Recommender Library: Recommended approproaches, Item-Scorer, Estimator 
- Data Science / AI practitioners:
    - Analyst, Data Scientist, Machine Learning (MLE), Software Engineer... 
-- SEEDS: biweekly workshop for improving data science practitioners - defining consistent standards or terminology? 
    - isaac_storch@intuit.com (volunteering?)
- Python tooling and automation 
    - Services: Rest, GraphQL, AI orch; Lambdas:; Machine Learning Models: Scikit xgboost, Tensor flow, PyTortch?
Poetry may or not be one tool to solve everything? PyPI
- 

<h3>Automate City Data: Python</h3>
- Philip James: phildini@phildini.net 
- Involved in multiple companies: Crowdalert.com , etc... 

<h3>Pyscript</h3>
- PyScript [QR Code link](https://fpliger.pyscriptapps.com/talks-pybay-2024/latest/)
- Platform that allows you to write proper python? 
- Concern about bandwidth, security, 
- Start with [PyScript](https://pyscript.net/)

``` <script type="mpy" scr-"./main.py" config="./pyscript.toml"></script> ```
- alternative version

``` <script type="mpy" scr-"./main.py" worker async></script> ```

- Python editor element as well, LTK newer framework based on JQuery, PuePy?, BeeWare?, React Pyscript, Tufts has been using Pyscript this last year?
  
<h3>13 Fun Facts about Pythons</h3>
- update accordingly? 
- Email: allardbrain@gmail.com


TODO: 
- Get a signed copy of the book? Or just look at it? IDK? WHY?
- Follow-up with any the sponsors from this event?
- [Kwargs refresher](https://book.pythontips.com/en/latest/args_and_kwargs.html)
- Ignore downstream deviations

