# StreetEasy NYC Building Energy Usage Coding Exercise

Hello! Thanks for your interest in applying for the Ruby on Rails developer position at StreetEasy. This is the work sample that we use to evaluate your development skills. 

## Instructions
Using your knowledge of Ruby on Rails >= 4.2 generate a Rails app that calculates NYC building energy usage per year and displays the report on a page. This project should take >= 90 mins.

## Requirements

### Application should:

* be built in Rails >= 4.2
* use a SQLite relational database
* contain at least 3 ActiveRecord models
* use server side ERB templates, no Haml or Slim, React or Angular..etc 
* seed data from NYC Open Data's JSON api
* be responsive/mobile ready

As a user on the site I am able to see a list of all building addresses with measurements totals by year. The user should be able to toggle the year via a drop down control. 

### Sample
![ScreenShot](https://raw.github.com/StreetEasy/nyc-eu-codning-exercise/master/energyusage_report.png)

### Seeding Source Data
NYCData Energy Usage Api Url: https://data.cityofnewyork.us/resource/dnpn-ts5d.json
https://data.cityofnewyork.us/Environment/Energy-Usage-From-DOE-Buildings/mq6n-s45c

### Tips/Suggestions

* Specs are not necessary, but we sure do like them ;)
* Feel free to use any gems or libraries you would like

### Submitting your solution
Once your exercise is complete, commit your work, create a patch file and send that to us. Please _do not_ fork this public GitHub repo. We don't want other people copying your work! To create the patch:

``` git format-patch origin/master --stdout > nyc-eu-coding-exercise-[your last name].patch ```

Good Luck and Enjoy!


