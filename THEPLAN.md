### MVD Features 
- users can create quizzes
  - constructive forms for creating quizzes
  - multiple choice forms and text forms available
  - privacy: users can make their quiz unlisted (url can be visited)

- users can attempt a quiz
  - users can see the results of their recent attempt
  - users can share a link to the result of their attempt

- tumblr/pinterest style homepage/dashboard of all extant quizzes 
  - users can share a link to a single quiz
  - users can see a list of public quizzes
  - users can see a list of public quizzes on the home page

- ajax the quizzes to remove scrolling
- account locked edit and delete for quizzes
- 1000% gotta be a Multi Page App combo thingy


###  Stretch Features
- search bar for public quizzes and users
- like/share/report buttons
- quiz custom styles through SASS
- ai based quiz inspiration widget
- account profile pictures attached to quiz

###  User Stories 
- as a ________ i can _________ because ________

###  Be RESTFUL 
- BROWSE:  GET   -->  /quiz
- READ:    GET   -->  /quiz/:id
- EDIT:    POST  -->  /quiz/:id
- ADD:     POST  -->  /quiz
- DELETE:  POST  -->  /quiz/:id/delete


users can share a link to a single quiz
users can see a list of public quizzes
users can see a list of public quizzes on the home page


### skip the login,

### `http://localhost:3000/login/2
### app.get('/login:id', (req,res) => {
###   req.session.user_id = req.params.id
### });`
