Rally Team Member Burndown Chart
======================

![Title](https://raw.github.com/jonshippling/TeamMemberBurndownChart/master/screenshots/TeamBurnDown.png)

## Overview

The Team Member Burndown Chart app can be used to view the task progress relative to time remaining in any iteration, for any member of the team.
This application was modified from the Personal Burndown Chart provided by Rally.


<b>CAUTION:</b> Personal burndown charts are somewhat controversial. Some people have very strong opinions against such reports. You are cautioned against using this information, as with most Rally and Agile practices, to measure or rate the performance of an individual.

## How to Use

### Running the App

If you want to start using the app immediately, create an Custom HTML app on your Rally dashboard. Then copy App.html from the deploy folder into the HTML text area. That's it, it should be ready to use. 
See [this](http://www.rallydev.com/help/use_apps#create) help link if you don't know how to create a dashboard page for Custom HTML apps.

### Using the App

The info this app provides include:

* Viewing assigned task hours over time
* Viewing an ideal burndown line based on work assigned to you in the iteration (flat lines indicate weekends)
* Hovering over a bar or line to see detailed figures for the date
* Selecting past and future iterations using the Iteration drop-down menu
* Selecting any member of the team using the Current Member drop-down menu to view charts
* Typing in the Current Team Member drop-down menu filters team members by inputted string

<b>NOTE:</b> 

* This chart works best for teams that assign many or all of the tasks at the start of the iteration and update the to do values for their tasks <u>daily</u>
## Customize this App

You're free to customize this app to your liking (see the License section for details). Since this app uses a very old version of Rally's SDK, the app is only presented in its deployed form.

## License

PersonalBurndownChart is released under the MIT license. See the file [LICENSE](https://raw.github.com/RallyApps/PersonalBurndownChart/master/LICENSE) for the full text.
