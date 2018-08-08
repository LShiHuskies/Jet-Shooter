# SpaceShip-Shooter App

A single player SpaceShip Traveler that shoots down planets for active gamer enthusiasts inspired by Asteroids.

The objective of this game is stay alive as long as you can and get the highest score you can get. Each time you shoot a large planet, you score 200 points and the planet shrinks in size and if you shoot it again, it will disappear and you score an additional 100 points.

As the game goes on and your score increases, the difficulty goes up as the planet gets faster and faster.
The controls of the game are ASWD as A is to go left, S is to go down, D is to go right and W is to go up. The arrow keys determine the direction you are looking at which determines which direction you are going to fire which is the enter key.

A user can create a new account and log in. If a user does not create an account and sign in, he or she can elect to simply click submit and the game will simply start, however his or her high scores will not be registered.

# Direction on how to run and start the program

1. Fork and clone this repository to your local environment.
2. Navigate to the file directory from your terminal.
3. Run 'bundle install' to install all required gems for the backend.
4. Run 'rails db:migrate' to set up database on the backend's directory.
5. Run 'rails s -p 4000' to start the server.
6. Navigate to http://localhost:4000/ and this will be the backend's database server.
7. Run npm start and you should be prompted to http://localhost:3000/
8. For a quick demo, simply click submit and the game will start.
