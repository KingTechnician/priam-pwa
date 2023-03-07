# Priam PWA

## Purpose (**NOTE: Check out the [Priam](https://www.github.com/kingtechnician/priam) application README before reading this.**)



As of now, there is a totally working Flask application I created that will work on the web.

That application will determine if the Priam app will be a useful tool for Virginia State University students, and if there is a demand for such an application.

That is where this version comes into play. Priam PWA will be a way to bring the Priam application as an installable application on Windows, Mac, iOS, and Android devices.

This also comes with a new, sleek React user interface to bring a more mobile experience.

Ideally, this would be called "Priam 2.0", but research and testing is still being done to determine if this indeed can serve as the next generation of the Priam application.

## Display (Subject to change as more features are added)




https://user-images.githubusercontent.com/104329626/220188611-f996da6a-0487-4e5f-a8f7-acf8fdd0079d.mp4





https://user-images.githubusercontent.com/104329626/220188647-23c85129-755e-42b7-b51a-e2f6c3dabcb2.mp4





## Steps to a 1.0.0 Production (Complete!)

- [x] User has the ability to login using VSU email
- [x] Only VSU emails are allowed to validate and pass login
- [x] Profile username is recognized by the application
- [x] User can query server posts
  - [x] By Title
  - [x] By Description
  - [x] By Tags
- [x] User can filter server posts
  - [x] By Date
  - [x] By Upvotes
  - [x] By Tags
- [x] User can create a post with a Title and Description
- [x] User can add tags to created posts
- [x] Users are able to upvote desired posts, which are also stored in a server

## Current Stage: Ensuring Security
- [x] Keeping important values in-memory and inaccessible via browser
- [ ] Validating people accessing the AWS Lambda Functions through Auth0 tokens
- [ ] MFA
- [ ] Ensuring CORS policy for AWS Lambda Functions
