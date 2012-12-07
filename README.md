Rally Personal Burndown Chart
======================

![Title](https://raw.github.com/RallyApps/PersonalBurndownChart/master/screenshots/title-screenshot.png)

## Overview

The Personal Burndown Chart app can be used to gain visibility into your personal task progress relative to the time remaining in the iteration. 

<b>CAUTION:</b> Personal burndown charts are somewhat controversial. Some people have very strong opinions against such reports. You are cautioned against using this information, as with most Rally and Agile practices, to measure or rate the performance of an individual.

## How to Use

### Running the App

If you want to start using the app immediately, create an Custom HTML app on your Rally dashboard. Then copy App.html from the deploy folder into the HTML text area. That's it, it should be ready to use. See [this](http://www.rallydev.com/help/use_apps#create) help link if you don't know how to create a dashboard page for Custom HTML apps.

Or you can just click [here](https://raw.github.com/RallyApps/PersonalBurndownChart/master/deploy/App.html) to find the file and copy it into the custom HTML app.

### Using the App

The info this app provides include:

* Viewing assigned task hours over time
* Viewing an ideal burndown line based on work assigned to you in the iteration
* Hovering over a bar or line to see detailed figures for the date
* Selecting past and future iterations using the Iteration drop-down menu

<b>NOTE:</b> 

* This chart works best for teams that assign many or all of the tasks at the start of the iteration and update the to do values for their tasks daily
* By default, the ideal burndown trend line assumes that no work is being done on the weekends. This can be changed to a straight line by setting the WORK_WEEKENDS variable to true. To do this, you will need to cut and paste the app source code into a new Custom HTML app

## Customize this App

You're free to customize this app to your liking (see the License section for details). Since this app uses a very old version of Rally's SDK, the app is only presented in its deployed form.

## License

PersonalBurndownChart is released under the MIT license. See the file [LICENSE](https://raw.github.com/RallyApps/PersonalBurndownChart/master/LICENSE) for the full text.
