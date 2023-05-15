## Idea spitballing:

- Anime type app
- what animes have dub or not/ subs or not
- IMDB clone?
- Auto generate suggestions
- More anime finder/engine
- Have watched tracking
- Account creation ability


## Requirements:

- [] two table minumum: 
> User(login, email, genre_preferences, password, password_verification)<br>
> Anime (name, year, genres, runtime, synopsys, seasons, episodes, studio) Stretch goal: add director, actors and others.

- [] user authentication with devise:
> We can have a landing page for everyone<br>
>> that allows login/signup<br>
>> Information about the application itself<br>
>> stretch goal (SG): have a caroussel for the landing 

> Signup:
>> Add a preferences checklist

- [] CRUD:
> Create: account creation, watchlist creation, multiple watchlist (SG)<br>
> Read: index, protected index, api that populates the index<br>
> Update: personal list updating, personal info updating (SG)<br>
> Delete: delete a personal list, delete account (SG)


### Green Light Meeting
- [ ] Elevator pitch - 30 sec summary of the app
- [ ] Wireframes - visual representations of all the pages your user will see for your MVP
- [ ] DB schema drawn out with column names, data types, and table relationships
- [ ] CRUD actions
- [ ] User stories for your MVP on Trello
