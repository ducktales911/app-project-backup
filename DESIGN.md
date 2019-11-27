Based on your proposal, you can now start studying your problem in a more technical fashion. 
Map the separate parts of the solution onto the framework(s) that you are using. 
What APIs, methods or techniques do you need to implement each feature?

Think about and fully express how the user interface will be handled, 
where the data is coming from, 
and how the various parts will work together to form a complete application.

The teaching staff and your fellow students can help you spot fundamental problems that need to be solved, 
or if technical limitations will likely prevent you from finishing the project.

It is expected that you separate, in your code, handling of the user interface from data management 
and from complex algorithms whenever possible. 
It should be clear from your design document how you are going to do this!

#### Some parts that you should describe here:

- advanced sketches of your UI that clearly explain which features are connected to which underlying part of the code (e.g. where the database is accessed and what for)

![Sketch](https://github.com/ducktales911/app-project/blob/master/doc/Flow%20app.png?raw=true)

Update de schets van de proposal in sketch: 
  - vooralsnog 1 scherm
  - een lijst met taken, onder elke taak een progress bar
    - connected to which underlying part of the code?
  - nog geen hamburger menu nodig
  - gebruik in eerste versie een + knop voor toevoegen taken
    - connected to which underlying part of the code?
  - gebruik time picker: eerst op "domme" locatie boven toetsenbord. hoeft nog niet te scalen.
    - connected to which underlying part of the code?
  - gebruik vooralsnog 1 timebox per taak (dus nog geen pauzes / pomodoro's)
  - main timer bovenin en individuele timers per taak
    - connected to which underlying part of the code (swift Timer class?)
  - notificaties met Quick Actions
    - connected to which underlying part of the code?

- a diagram of utility modules, classes and functions that you will need to implement, in appropriate detail

- a list of APIs and frameworks or plugins that you will be using to provide functionality in your app
- a list of data sources if you will get data from an external source, including information on how your are going to filter and transform the data for your project
- a list of database tables and fields (and their types) if you will use a database

### Bronnen
Voor de list interface:
https://www.raywenderlich.com/2153-how-to-make-a-gesture-driven-to-do-list-app-like-clear-in-swift-part-1-2

Voor de meldingen:
Google: Local notifications

Voor de database (eerste versie):
https://github.com/stgm/rester/blob/master/rester.py

Voor timers (algemeen):
https://www.hackingwithswift.com/articles/117/the-ultimate-guide-to-timer
https://medium.com/ios-os-x-development/build-an-stopwatch-with-swift-3-0-c7040818a10f
https://www.youtube.com/watch?v=jRuvuSNKSEo

Voor de main timer interface: 
https://stackoverflow.com/questions/30289173/how-to-create-a-circular-progress-indicator-for-a-count-down-timer

