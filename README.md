# Docker
This is a sample repository for the docker task for creating a CI/CD pipeline.
Steps for creating the CI/CD pipeline 

a. create a github repository for keeping your application at place . 
b. create a application that you want to push into your docker container.
c. intiaalize a git repository locally 
d. link your git to your github 
e. push your local repository to your github repository.
f. create a dockerfile in the root directory of your project .
g. in the github actions-->new workflow-->main.yml
h. configure secrets ...setting-->secrets and actions-->new secret
i. commit your changes to the .github/workflows/main.yml file and push them to your GitHub repository:


git add .github/workflows/main.yml
git commit -m "Add GitHub Actions workflow"
git push origin main

you can see the workflow of the application you have created in your github. 

Depending on your application, you'll need to add specific deployment. This could involve SSH-ing into a server, deploying to a cloud service, or using Kubernetes.
![image](https://github.com/ananyashree2407/Docker/assets/83506143/c5583ec3-1add-49fb-9380-d7ae648e67db)

![image](https://github.com/ananyashree2407/Docker/assets/83506143/848cc405-d2eb-4f94-80ef-90d4ddbcb259)
this is the output on the docker GUI you will get once your docker image is properly loaded and run. 

![image](https://github.com/ananyashree2407/Docker/assets/83506143/ff08c120-5191-4513-bab4-412d732f1373)

![image](https://github.com/ananyashree2407/Docker/assets/83506143/9cdaa594-c76a-4583-ac1e-ec6fff0f2c0f)

P.S. As I am new and trying to learn the technology ...using the CLI is not at all easy but can be learnt!!!



