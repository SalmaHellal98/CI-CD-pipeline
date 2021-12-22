# Creating CI/CD Pipeline for Python Project using :

## 1. GitHub actions : 

Continuous integration (CI) is a software practice that requires frequently committing code to a shared repository.

When I commit code to my repository, I can continuously build and test the code to make sure that the commit doesn't introduce errors. 
Here, I used **GitHub actions** that offer CI workflow template and I used **Pytest** to test my **Hello world Flask** application.

### Test results with **Pytest** : 

![Test1](./screenshots/devops1.PNG)

![CI](./screenshots/devops3.PNG)


## 2. Heroku for deployment : 

Continuous deployment is a strategy for software releases wherein any code commit that passes the automated testing phase is automatically released into the production environment, making changes that are visible to the software's users.

### Deploying the flask app on Heroku : 

* Install Heroku CLI
* Login to Heroku CLI session: heroku login
* Create new Heroku App: heroku create
* Generate Authentication Token: heroku authorizations:create

'Deploy to Heroku' Action:

![heroku_action](./screenshots/deploy_to_heroku action_.PNG)

#### Deployment result on heroku :

![build](./screenshots/deployment.PNG)

![CD](./screenshots/devops4.PNG)
