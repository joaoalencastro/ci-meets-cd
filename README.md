# ci-meets-cd
Testing purposes repository. I'll create infrastructures creation jobs work with circleci.

## Steps:
 - CircleCI is hooked to the project. 
    That means that when we push changes to the repository, CircleCI is notified and has to refresh its resources and execute its configuration file.
 - Build workflow.
    The .circleci/config.yml file has a workflow in which runs the necessary jobs to create a stack with AWS CLI using the providade template in aws directory.
