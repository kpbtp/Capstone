# Team Name

**Kevin's Peanut Butter Treasure Planet!**

# Team Composition

Product Manager: Borja Xaire<br>
Project Manager: Brandon Johnwell<br>
Tech Lead: DeMario Ward<br>
Design Lead: Jose Salas<br>

# Project Overview 

### Elevator Pitch:

Welcome to the Anime Repository App: ARA! The ultimate destination for anime enthusiasts. 

ARA is a groundbreaking online platform dedicated solely to the world of anime. Our mission is simple: to provide you with a comprehensive database of anime content so that you can find what you like, not only what's currently popular. 

Whether you love your 80's Crying Freeman or the latest Kimetsu No Yaiba; at ARA, you can explore our vast library of anime titles spanning across genres, eras, and styles. We provide you with the means to learn more about your favorite anime and add it to your own custom lists. 

It doesn't matter if you are a seasoned otaku or just starting your anime journey, ARA is the go-to place to discover your next obsession.

ARA goes beyond a simple database. We understand that each anime fan has unique tastes and preferences. With ARA, you can curate a personalized list of anime that matches your interests, ensuring that you never miss out on the next anime gem.

Join us at ARA and embark on an unforgettable journey into the world of anime.

### Wireframe:

Wireframe link: https://www.figma.com/file/FWk28WnjSsFyIx4iP0Tuvs/Untitled?type=design&node-id=2%3A2&t=Q2UQ3KTITRCYweBZ-1

### Database Schema:

#### Models' Relationships:

class User < ApplicationRecord<br>
  has_many : anime_lists<br>
  has_many : animes, through: :anime_lists<br>
end<br>
<br>
class AnimeList < ApplicationRecord<br>
  belongs_to :user <br>
  belongs_to :anime <br>
end<br>
<br>
class Anime < ApplicationRecord<br>
  has_many :anime_lists<br>
  has_many :users, through: :anime_lists<br>
end<br>
<br>

![DB Schema](https://github.com/kpbtp/Capstone/assets/127794065/aedc3dfa-87e5-46a2-86ce-6ff5718c9d41)

### Crud Actions:

Create: account creation, watchlist creation, multiple watchlist (SG)<br>
Read: index, protected index, api that populates the index<br>
Update: personal list updating, personal info updating<br>
Delete: delete anime from personal list, delete a personal list / delete account (SG)<br>


# Project Technologies

### Backend 
- Ruby
- Rails

### Frontend
- React
- Tailwind
- Bootstrap
- Reacstrap
- Three.js
- Skybox AI


