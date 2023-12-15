#  MVD Features 
 - multiple choice forms vs text forms
 - ajax the quizzes to remove scrolling
 - constructive forms for creating quizzes
 - account locked edit and delete for quizzes
 - tumblr/pinterest style dashboard of all extant quizzes 


#  Stretch Features
 - search bar for public quizzes and users
 - like/share/report buttons
 - quiz custom styles through SASS
 - ai based quiz inspiration widget
 - account profile pictures attached to quiz

#  User Stories 
 - as a ________ i can _________ because ________

#  Be RESTFUL 
 - BROWSE:  GET   -->  /quiz
 - READ:    GET   -->  /quiz/:id
 - EDIT:    POST  -->  /quiz/:id
 - ADD:     POST  -->  /quiz
 - DELETE:  POST  -->  /quiz/:id/delete



## skip the login,
### `http://localhost:3000/login/2
### app.get('/login:id', (req,res) => {
###   req.session.user_id = req.params.id
### });`