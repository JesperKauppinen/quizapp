# Quiz web app
Where you can create your own quizzes, play in numerous of quizzes and compare your statistics with others in the Leaderboard of each challenge.


## Purpose
This project was made as part of the weekly programming challenge hosted by [DevJam].
The project was made for learning purposes.
### What I learned
Once again I learned lots of new things. For the first time I used Bootstrap. I also learned how to order database query in sqlalchemy.
## [Live Demo](https://jeb-quiz.herokuapp.com/quiz/play/)
Quiz page:
![image](https://user-images.githubusercontent.com/76889226/146368139-39963470-4887-4bcb-8517-cdcbd42ef2b9.png)
Leaderboard page
![image](https://user-images.githubusercontent.com/76889226/146368751-45191415-3fe8-4ff0-b6e2-9472a01d2374.png)




## About the Challenge
#### π  Difficulty Level (of user stories): Beginner 
π Start: December 10th<br>
π Deadline: December 16th 16:00 (4PM) GMT

#### π Project Description
Practice and test your knowledge by answering questions in a quiz application.
As a developer you can create a quiz application for testing coding skills of other developers. (HTML, CSS, JavaScript, Python, PHP, etc...)

##### πUser Stories
- βοΈ User can start the quiz by pressing a button.
- βοΈ User can see a question with 4 possible answers
- βοΈ After selecting an answer, display the next question to the User. Do this until the quiz is finished
- At the end, the User can see the following statistics:
   * βοΈ Time it took to finish the quiz
   * βοΈ  How many correct answers did he get
   * βοΈ  A message showing if he `passed` or `failed` the quiz
##### π Bonus features

- βοΈ User can share the result of a quiz on social media
- βοΈ Add multiple quizzes to the application. User can select which one to take
- βοΈ User can create an account 
- β    User have all the scores saved in his dashboard. User can complete a quiz multiple times
- βοΈ User can create their own quizzes

##### β¨ Custom features (not part of the challenge)
- βοΈ Leaderboard for every challenge

## Tech

The app is written in python using Flaks-library. 
Frontend is written in html5, css and vanilla js.
Backend uses Flask sqlalchemy and flask-login.
App is deployed in [Heroku].

#### Frameworks and libraries:

- [Flask] - Micro web framework written in python.
- [Flask-Socketio](https://flask-socketio.readthedocs.io/en/latest/) - Flask-SocketIO gives Flask applications access to low latency bi-directional communications between the clients and the server.
- [Flask-login] - Flask-Login provides user session management for Flask.
#### Deployment
- [Heroku] - Heroku is a cloud platform as a service supporting several programming languages.



## Installation and running

This app requires [python 3.7+](https://www.python.org/downloads/) to run.

Clone git repo
```sh
git clone https://github.com/JesperKauppinen/quizapp.git
```

After cloning or downloading this git repo, install required python libraries

```sh
pip install -r requirements.txt
```

run app.py
```sh
python app.py
```
### Deployment
App is hosted in heroku. Use `HEROKU` branch for heroku deployment as it also contains `Procfile`.


## Contribute?
Want to contribute? Awesome!  
This project was part of weekly challenges hosted by [DevJam] and won't be updated.
Maybe you would like to work with us, hit me up and let's talk. :)

## Credits
- [Scoreboard design](https://codepen.io/hakura/pen/ebglw) - Leaderboard design
- [Card design](https://codepen.io/hakura/pen/ebglw) - Cars design
- [Boostrap](https://codepen.io/hakura/pen/ebglw) - Some frontend elements like grids.
- [Fontawesome](https://fontawesome.com/) - Icons

## License
MIT


   [Flask]: <https://flask.palletsprojects.com/en/2.0.x/>
   [Flask-login]: <https://flask-login.readthedocs.io/en/latest/>
   [DevJam]: <https://discord.gg/nZBxGEudY6>
   [emojipedia]: <https://emojipedia.org/artist-palette/>
   [icons8]: <https://icons8.com/>
   [sharingbuttons]: <https://sharingbuttons.io/>
   [Handdrawn]: <https://fxaeberhard.github.io/handdrawn.css/>
   [imgbb]: <https://imgbb.com/upload>
   [Heroku]: <https://www.heroku.com>
