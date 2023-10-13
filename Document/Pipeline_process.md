## Circle CI Pipeline

### Architecture
!['pipeline flow'](/screenshots/pipeline-flow.png)

### Process
    - Create a Circle CI account using github account
    - Click on Follow Project for the github repository which has the .circleci/config.yml file
    - Add the necessary environment variables to your project settings
    !['environment'](/screenshots/circleCI/Evn.png)
    - git commit and push the changes to the branch will trigger the deployment process
    !['build'](/screenshots/circleCI/build.png)
    !['deploy'](/screenshots/circleCI/deploy.png)