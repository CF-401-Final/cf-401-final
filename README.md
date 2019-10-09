# 401 Java Final Project: Hands of Five

Team members: Travis Cox, Trevor Dobson, Steve Grant, Jane Hur, Renee Messick

Deployed site: https://master.d2681ag10jil74.amplifyapp.com/

Presentation deck: Coming Soon!

## Project overview:

Hands of Five is an app that allows instructors to gauge the understanding of their students in real time. Students are able to share their current level of understanding in an anonynmous way, allowing for more honest feedback.

## Technology/Services used: 

![connections](./assets/connections.png)
[Online connections diagram](https://whimsical.com/JhrDEJM1ed3ufaDECLaqYo)

### React

Our front end is a built as a [React](https://reactjs.org/) app. An instructor is able to post a question which students can respond to. Data is sent and received by the front end through an API Gateway Websocket connection. Results are updated and displayed in real time! 

We used [ReactBootstrap](https://react-bootstrap.github.io/) to design and style our app. 

### GitHub

[GitHub](https://github.com/) was used to manage our code and to document our project: 

- [Repo for Project Documentation](https://github.com/CF-401-Final/cf-401-final)
- [Repo for Frontend](https://github.com/CF-401-Final/frontend)
- [Repo for Lambda Functions](https://github.com/CF-401-Final/hands-lambda)

### AWS Amplify

We used an AWS service called [Amplify](https://aws.amazon.com/amplify/) to automate the build and deployment of our front end. Amplify was integrated with our frontend GitHub repo, so that updates to master would automatically start a process to build and publish our React app. 

![Amplicy](./assets/amplify.png)


### AWS API Gateway Websockets
### AWS Lambda Functions
- Connect
- Send/Receive Data
- Disconnect
### DynamoDB

## Project documentation

- [Wireframes](https://whimsical.com/Nc2w7CeyFZ73DDXcEMqgTB#2Ux7TurymNB6r2PosD1R)
- [Team Agreement](projectDocs/TeamAgreement.md)
- [Conflict Plan](projectDocs/conflictPlan.md)
- [Trello Board](https://trello.com/b/Rm0s1xSj/cf-401-final)
- [ER Diagram](Soon!)
- [User Stories](projectDocs/userStories.md)
- [Domain Modeling](projectDocs/domainModel.md)

## Screenshots

## Resources:
