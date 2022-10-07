# WattTime adds Central America with visual model to Climate TRACE. 
By collecting, predicting, and visualizing real-time emission data, energy 
providers can use cleaner energy sources.  
June 23, 2021. WattTime is excited to announce the addition of many countries in Central 
America to the Climate TRACE project. In addition, we are launching the beta version of an 
AI-driven forecasting model and visual tool that shows real-time emissions. All this new data 
will be open to the public domain to further the development of eco-conscious technology. 
The new data will also update coverage for the Automatic Emission Reducer (AER) 
technology for devices that don’t need a constant supply of electricity. The AER uses real-
time satellite imagery data combined with ground emissions data to detect when the power 
grid produces clean energy from wind/solar farms or dirty energy from sources like coal 
power plants. 
From companies looking to select cleaner manufacturing suppliers, to researchers trying to 
study the effects of climate change, to consumers making choices about their energy 
consumption, one thing is clear: a reliable way to measure where emissions are coming 
from and the ability to predict load is necessary. Currently this only data in a series of 
obscure webpages, if it is even published at all. Such a global problem needs a 
comprehensive tool that is easy to visualize. 
Our solution has been to use AI and data scrubbers to grab all the available information and 
synthesize it into a useful forecasting tool. This new tool will allow companies and 
individuals to make more informed decisions regarding air pollution. It will also be a great 
asset for universities and research groups interested in climate change and greenhouse gas 
emissions. Furthermore, this tool will be publicly available making the swap to green 
technology cost effective. 
   
 
   
 
Get started today by signing up at WattTime.org and connecting your devices. Start using 
the data visualization software to see all the features and let the AER automatically use 
clean energy.  
“We are excited to be contributing to a larger effort towards a sustainable future.” Said 
former President Al Gore. “The new features of Climate TRACE will help empower 
companies and individuals to make eco-conscious decisions. As we continue to collect more 
data from more regions, the power and potential of this technology will grow dramatically!” 
“The Climate TRACE’s new visualization tool has been a game changer.” Said Rebecca Black, 
chief data analyst at Microsoft. “With the advanced AI-based forecasting model we have 
been able to pinpoint potential sources of pollution with far greater accuracy.” 
“Our whole family began using WattTime’s AER technology when they announced coverage 
for Central America.” Said Jose Gomez, resident of Guatemala City. “We have it for our 
home, our outlets, and even our refrigerator. I’m so happy I can teach my children to be 
environmentally friendly without having to break the bank.” 
Go to our website to sign up as a visitor and begin exploring this new revolutionary 
technology today! You can make up to 10 connections per IP address while the technology 
is still in beta or contact us to gain more comprehensive access.  
FAQs 
1. What is our goal? 
By gathering information on power-grid operators and checking for accuracy, we enable the 
ability to forecast and visualize data around the world. We have started with Central 
America and are expanding.  
  
   
 
   
 
2. How do we get the emissions of the power grid? 
By utilizing publicly available values and scraping each major power-grid operator, we 
collect real-time data, trends, and historical data which can be resolved for any number of 
uses, such as our forecasting model.  
3. What is scrapping? How does this help collect data? 
Scrapping is fundamental to our project and is the process of creating specialized tools to go 
on the internet and gather information. By going to each major power-grid operator, we 
‘scrape’ information off their websites and reports for use in our own ways in real-time. 
4. What is this data? What does it represent? 
The data that is actively collected and stored contains information that correlates the 
emissions as well as the demands or load of each power-grid operator. This represents air-
quality as well as people’s regional use of electricity. 
5. What are you forecasting? 
The forecasts that are created will both anticipate load or demand of electricity on an 
hourly basis, as well as emissions or air-quality on an hourly basis. Users can easily check the 
accuracy by comparing previous forecasts to current data for themselves.  
6. How do you forecast emissions? 
Having scraped data available to us and using machine learning and specialized algorithms, 
we create predictions that specialize to each power grid operator based on their history and 
real-time trends. 
  
   
 
   
 
7. Where is this forecasting model available? 
We created an application that will host a web GUI. This GUI allows people to meaningfully 
interpret data about emissions and power grid use. This web GUI is then accessible to many 
devices thanks to it being on compatible with many browsers. 
8. How can we use application/model? 
Our efforts worked towards providing a simple to use and easy to understand interface. This 
can be used to view past emissions as well as predict emissions and allow users to control 
when and how they use their power. There is also the ability to export the real-time data 
reports that you currently see.  
9. Temporally, what does the data represent? 
This data is mostly targeted at real-time representations. However, by collecting real-time 
data, there is a buildup catalog of historical data! And by using both, we also create a 
forecasting model for future data as well. You can view data that is a week old or 3 days into 
the future. Win-Win-Win 
Internal FAQs 
1. What will customers like most about WattTime? 
Our API allows the user to enter a zip code and see the power grid usage history and 
forecast of that location, along with a rating of cleanliness associated to time of day. As well 
as an interactive map where you can zoom in to the area of interest to inspect cleanliness of 
power in the area. WireFrame Modeled. 
2. What are privacy concerns with this product? 
There are none. Our data collection is targeted at very specific energy and power plant 
websites. We do not collect data from our users. 
   
 
   
 
3. What is our primary language protocol? 
Our back-end code is written primarily in Python 3 and expected to be Pep8 compliant and 
processed through flake8. Pep257 is encouraged. Relative imports are restricted to the 
following: Datetime, Dateutil, Pytz, Requests, and Pandas. 
4. How to collect data? 
Data is collected from scraping power grid websites across the globe. We focused on 
Central America, with countries of Panama, El Salvador, Costa Rica, Nicaragua and Honduras 
and everything in between.  The data returned by a scraper is in a list of dictionaries where 
each dictionary corresponds to a single datapoint. 
5. Primary problems, and common solution in data collection 
Data accuracy. Data was analyzed for accuracy. Many coal-fired power plants report 
emissions in units that make their data look 1000 times smaller than even possible. Data 
was stored and compared for accuracy. Power plant data is expected to refresh in 5-minute 
intervals. Weekly common trends are expected, and outliers highlighted for further 
inspection. 
6. Can only people with AER compatible smart devices benefit from our product? 
No. Not only will the data collection be invaluable towards a complete global picture of 
power consumption. But even on a more personal basis, anyone living within the region we 
specifically grab data from will have access to our online API and can find out information 
about their own local power cleanliness. Even without AER compatible devices, simple 
behavioral changes made from the general public can have a dramatic impact on peak 
“dirty” hours, and we will empower them with the tools that is our WattTime Senior 
Capstone Project.