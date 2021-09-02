# Tableau - Airbnb
## Objective
To use Airbnb data to find out business insights and to visualize it via Tableau Dashboard <br>
Here is the link of the Tableau visualization:
https://public.tableau.com/app/profile/constance3864/viz/AirbnbParis-DashBoard/Dashboard1

![Paris](/images/parisairbnb.jpeg)

## Dashboard
![Dashboard](/images/Airbnb-Paris.png)

## Table of Contents
1. Data Collecion
2. Dashboard
  * Basic Information<br>
    * Map View<br>
    * Room Type<br>
  * Analysis View <br>
    * Past Sales <br>
    * Top 10 Busy Hosts <br>
    * Future Maximum sales

## 1. Data Collection
We use the data from Airbnb - http://insideairbnb.com/get-the-data.html <br>
Here are the details of this project:
* City chose from Airbnb - Paris
* File used - listings.csv
* Tableau version used - Tableau Public

![Data](/images/Data_Paris.png)

## 2. Dashboard
### Basic Information
#### 1/ Map View <br>

We put the [Average Price] in the [Neighbourhood] (20 regions in Paris) <br>
each circle size represents the amount of [Average Price]. <br>
[Average Price] ranging from 75.4 to 212.3 EUR, with the mean 113 <br>

As you can see the Top 3:<br>
1. Elysee has the highest as 212.3 EUR
2. Louvre 165.1 EUR
3. Palais-Bourbon 163 EUR

all are close to famous sightseeing places in Paris - Champs-Élysées, Louvre Museum, Eiffel Tower <br>
and the lowest average price neighbourhood mostly located on the surroundings of Paris, for the East surroundings has the lowest 3 regions.

![Map](/images/ParisMap.png)
![Map](/images/attraction.gif)


#### 2/ Room Type <br>
There are 4 types of room, Entire home/apt, Hotel Room, Private Room, Shared Room <br>
Entire home/apt takes up 85% of total, where Private Room takes 12%

![RoomType](/images/RoomType.png)

### Analysis View
#### 3/ Past Sales <br>
We use the available data to make assumptions on annual sales:<br>
[Price] x [Minimum Nights] x [Reviews Per Month] x 12 <br>

Top 3 Sales, total sales &  its average price:<br>
1. Buttes-Montmartre - 13.2 M Eur - 87.2
2. Popincourt - 12.9 M - 91.9
3. Bourse - 12 M - 142.6

Here are the findings: <br>
1 - the regions are evenly distributed across the top 10 cities, there're only 1M EUR difference between each rank.
In some other cities, it can be very extreme, only focus on 1-3 regions.<br>
2 - Top 2 sales, the average price is the lowest 5 & 6 regions, as 87.2 & 91.9 which is lower than the mean 113
it could imply that the airbnb consumer for Paris prefer an economy stay. 

![PastSales](/images/PastSales.png)

#### 4/ Top 10 Busy Hosts <br>
We have found out the Top 10 Busy Hosts. <br>
So that Airbnb and can contact them for collaborations: <br>
e.g. feature their stay in the webpage, there must be some reasons/charateristics for them to be so popular, by featuring them could attract more customers, even if this is full, will arouse customers' interest (giving hope) to search for second options.

![Top 10](/images/Top10%20BusyHosts.png)

#### 5/ Future Maximum Sales <br>
Since the maximum sales Airbnb could make highly depends on the availability of the stay. The available of stay in a year X the price ([Availability 365] x [Price]) will be the potential maximum sales Airbnb could make. So that decision makers would know what actions could take based on these availbility. <br>
As from graph, we can see the top 3 as:<br>
Passy - 88M EUR
Elysee - 72M EUR
Temple - 63M EUR
These 3 places take up around 23.7% of total future sales. Though the number are not extreme. 
We would recommend the company to post some attractions / activities / excusions package for clients to join in these potential area, so that would hope the consumer to choose these area.


![Potential Sales](/images/PotentialSales.png)

## Conclusions
Tableau Dashboard is meant to be 1 page for management to have a glimpse of the data, therefore we only work on 1 page. That means we have to prioritize what we want to show from our findings.
We chose to show basic information and some analysis.
The ultimate goal of airbnb is to lease out as much home as possible. So our aim is to find out which area has the most potential for the company to advertise or push.

## Challenges
1. Tableau Public has less functions than Tableau Desktop, having limitations to create beautiful maps
2. Tableau Public for some reasons works very slow on my Mac, so I have to choose a simple data set with 8.6MB than full version (140MB) to avoid computer lag and loading time.

## Next steps
the data set is very interesting, for data analysis purpose can work on python to have a deeper analysis

