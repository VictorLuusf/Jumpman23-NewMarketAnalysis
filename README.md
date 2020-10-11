  <h3 align="center">Jumpman23 Challenge</h3>

  <p align="center">
    This project is from an interview challenge, I completed it utilizing pandas, numpy, matplot, seaborn and a python mapping library called folium.
    <br />
    <a href="https://github.com/VictorLuusf/Jumpman23-NewMarketAnalysis"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/VictorLuusf/Jumpman23-NewMarketAnalysis">View Demo</a>
    ·
    <a href="https://github.com/VictorLuusf/Jumpman23-NewMarketAnalysis">Report Bug</a>
    ·
    <a href="https://github.com/VictorLuusf/Jumpman23-NewMarketAnalysis">Request Feature</a>
  </p>
</p>


  <p align="center">
  
**Background**
  
Jumpman23 is an on-demand delivery platform connecting “Jumpmen” and customers
purchasing a variety of goods. Jumpman23 will send Jumpmen to merchants to purchase and
pickup any items requested by the customer. Whenever possible, Jumpman23 will order the
requested items ahead to save the Jumpmen time. Each time a Jumpman23 delivery is
completed, a record is saved to the Jumpman23 database that contains information about that
delivery. Jumpman23 is growing fast and has just launched in its newest market -- New York City.

**Challenge**

The CEO of Jumpman23 has just asked you how are things going in New York? The CEO is
considering pouring more resources into NYC and wants you to come up with a plan to grow the
market by 20% in two months.

They have also heard of data integrity issues in the data from NYC. Please think through the
CEO’s ask and present to both the CEO and the CTO, in any format you choose, an analysis of
the market. In addition, dive into the reports on data integrity issues and if they indeed exist,
outline where they may be and how they may impact the analysis. The CEO is a visual learner,
the CTO loves to see code and technical work, and both are obsessed with maps.

**Available Data**

You have been provided one small csv file with a sample of data. This file includes:

● Job_ID -- > a unique identifier of a delivery

● Customer_id → a unique identifier for the Jumpman23 customer

● Jumpman_id → a unique identifier for the Jumpman who completed the delivery

● vehicle_type → The method of transport the Jumpman used to complete the delivery

● pickup_place → The name of the Pickup location

● place_category → A categorization of the Pickup location

● Item_name → the name of the item requested

● Item_quantity → how many of that item was requested

● Item_category_name → categorization provided by the merchant, think “appetizers”,
“soups” etc

● How_long_it_took_to_order → how long it took to place the order [interval]

● pickup_lat → the coordinates of the pickup location

● pickup_lon → the coordinates of the pickup location

● dropoff_lat → the coordinations of the dropoff location


● dropoff_lon → the coordinations of the dropoff location

● when_the_delivery_started→ localized timestamp representing when the delivery began

● when_the_Jumpman_arrived_at_pickup → localized timestamp representing when the
Jumpman arrived at the pickup location

● when_the_Jumpman_left_pickup → localized timestamp representing when the Jumpman
left the pickup location

● when_the_Jumpman_arrived_at_dropoff → localized timestamp representing when the
Jumpman reached the customer



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)



<!-- ABOUT THE PROJECT -->
## About The Project

As part of the analysis challenge, I was asked to provide my work both visually, include my code/technical work as well as include maps.

### Built With

* [juypternotebook](https://jupyter.org/)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

You will need to install these libraries if you don't already have them. You will need to load up terminal if you are on Mac, Command prompt if you are on PC. If you are using python via Anaconda, you might want to use Anaconda Prompt.
* Pandas
```sh
pip install pandas
```

* Numpy
```sh
pip install numpy
```

* Matplotlib
```sh
pip install matplot
```

* Seaborn
```sh
pip install seaborn
```

* Folium
```sh
pip install folium
```

<!-- USAGE EXAMPLES -->
## Usage

You can use this to see how to use pandas, numpy, seaborn, matplotlib or folium.

Folium is actually a very powerful tool. You are able to zoom in and see the count of rows of data by county, city, and zipcode
![alt text](https://github.com/VictorLuusf/Jumpman23-NewMarketAnalysis/blob/main/code%20snippets/Folium.PNG)

This is an example of how you can use seaborn to create multiple box plots to examine your data.
![alt text](https://github.com/VictorLuusf/Jumpman23-NewMarketAnalysis/blob/main/code%20snippets/Multibox%20plots.PNG)
