# webApp
Learning how to create WEB APP using Golang and Templates
I decided to create my Web project using Go, that is just a prototype I made to further development of
my own UNO and other games website.

/cmd/web contains the most important parts of web app. routes.go creates a mux server and handles /home and /about pages using middleware.go

/templates contains .tmpl files that are used to send and maintain up-to-date info.

/pkg/config contains the main structure of the app using Struct

/pkg/handlers contains handlers to make the site works


