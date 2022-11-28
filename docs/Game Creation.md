---
layout: default
title: Game Creation
nav_order: 3
---

# Game Creation
{: .no_toc }

On the lobby page, you are able to create a game. Please note that only users with admin access should create a game.

The easiest way to start a game would be to pick an identifying unique name for your game and click on:


![Create Game](https://github.com/CodyCodingCode/Covid-35/blob/gh-pages/assets/images/create_new_game.png?raw=true)


Notice that a password is not required for game creation.

### Custom Settings

As you can see there are also custom settings available for you to change, if you so choose. Be careful, however, as changing a few settings can drastically
change the outcome of the game. If you don't feel comfortable with changing certain parameters, it's best to leave them as their default value. 

## Game Settings
### Asymptomatic Transmission Rate:
The transmission rate of Covid-35 amongst those who have Covid-35 but are asymptomatic.
Default: 0.4

### Symptomatic Transmission Rate:
The transmission rate of Covid-35 amongst those who have Covid-35 and are also showing symptoms.

Default: 0.3

### Diagnosed Transmission Rate:
The transmission rate of Covid-35 amongst those who have Covid-35 and have been diagnosed with
having Covid-35 and are thus much less likely to pass along the virus to others.

Default: 0.01

### Inverse Mean Latent Period:
The rate at which the exposed population becomes infected

Default: 0.25

### Asymptomatic Percentage:
Fraction of the population who have Covid-35 but are asymptomatic.

Default: 0.35

### Asymptomatic Healing Rate:
The rate at which people who are asymptomatic with Covid-35 recover from Covid-35.

Default: 0.07

### Asymptomatic Detection Rate:
The rate at which asymptomatic carriers are detected by healthcare system.
Default: 0.000001

### Symptomatic Detection Rate:
The rate at which symptomatic carriers are detected by healthcare system.
Default: 0.9

### Symptomatic Healing Rate:
The rate at which people who have Covid-35 and show symptoms recover from Covid-35.

Default: 0.03

### Diagnosed Healing Rate:
The rate at which people who have Covid-35 and who have been diagnosed with Covid-35 heal from the virus.

Default: 0.04

### Symptomatic Mortality Rate:
The rate at which people who have Covid-35 and are symptomatic die from the virus.

Default: 0.0008

### Diagnosed Mortality Rate:
The rate at which people who have Covid-35 and are diagnosed with Covid-35 die from the virus.

Default: 0.0006

### Hospitalisation Rate:
The rate at which people who have Covid-35 end up being hospitalised.

Default: 0.065

### ICU Rate:
The rate at which people who have Covid-35 end up in the ICU.
Default: 0.235

### ICU Capacity:
The maximum ICU capacity

Default: 0.35

### Vaccine Efficacy on Sigma:
The effectiveness of the vaccine, used to calculate 

Defafult: 0.75

### Land Travel Supression:
By how much is land-based travel being suppressed.

Default: 0.5

### Air Travel Supression:
By how much is air-based travel being suppressed.

Default: 0.5

### Land Border Porosity:
The proportion of infected travellers detected by border screening through land-based travel.

Default: 0.73

### Air Border Porosity:
The proportion of infected travellers detected by border screening through air-based travel.

Default: 0.73

### Contact Tracing Effectiveness:
The effectiveness of contact tracing and by how much it reduces transmission.

Default: 0.1

### Vax Reduction of Hospitalisation:
The effectiveness of reduing hospitalisations once the vaccine has been introduced

Default: 0.99

### ICE Excess Mortality Rate:
Once the ICU is full, by much how much does mortality rate increase.

Default: 0.8

## Team Settings

### Starting Population
The starting population of the given country. 

### ICU Capacity
The base ICU carrying capcity of the given country.

### Initial Exposure
At the beginning of the game, how many people in each country are already exposed to Covid-35.

### Initial Popularity
The initial base popularity of the given country.

### Average Base ARP Per Turn
The ARP per turn is randomly generated every turn. Changing the average will change the range of ARP that can be generated. For example an average ARP per turn of 4 will generate ARP's between 3 and 5.
