## Welcome to my Today I Learned (TIL)-Blog

### 3.04.2020
#### Nothing so far

### 2.04.2020
#### Renovate rocks
#### Google sheets can import data from many sources, like urls? I will investigate that. 
#### Vue sloted properties

### 1.04.2020
#### Nothing so far

### 31.03.2020
#### Nothing so far :(
  
### 30.03.2020
#### Github actions is a dream to work with... [wip]
  ... if you come from older ci/cd tools like on-premise Bamboo, 
  where the build plan are seperated from the actual (git) project.
  
  Okay you could, depose a description of the build-plan to your (git)-project (mostly yml or "java-specs" exports),
  but you dont get the big benefit from buildplan-as-code: 
  
  The classic approach result more often to issues, if you want a specific feature-branch, which requires new build or deploy steps.
  With tools like github actions, you serve your build plan among the git branch, the build-agent will grab this file, read it and follow that instructions.
  If you change your build plan for the branch, the other branches are not affected.
  
  ```
  Todo: <insert nice graphics?> 
  ```
  Github actions is not the only service which provides so a services. There are travis, bitrise (i love bitrise for apple dependend deployment, maybe more in another post? ) and many more.
  A big benefit for Github actions are, that they are first class citizen in the github eco system and the onboarding works flawless.
  
#### Why I love serverless... in a nutshell [wip]
  * Network-stuff, I know the "basics" but i dont care, because im a dev und want try to things out.
  * clicki clicki clicke or wall of templates to do "simple" things
  * try to integrate renovate in our build pipeline, or: i want start a fargate container: 
   Part Container Stuff
    * setup docker registery
    * push to docker registry
    * IAM Roles who is allowed to consume (pull)
   Part VPC 
    * Create vpc
    * Create Subnet
    * Create Route Table
    * Create Internet Gateway
    * Create Security Group
   Secret Manager
    * Create Secret
    * Iam Role (who is allowed to consume)
   Part Fargate 
    * IAM Roles (ecsExecutionRole, execution)
   Part CloudWatch Events
    * Cron
    * IAM Roles (execution)
  * or use github.........
  
### 27.03.2020
####  Nothing so far :(

### 26.03.2020
#### CSS you can select all rows in a css-grid with: 
``` 
row-start: -1; 
```

### 25.03.2020
#### How simply you can create github pages
#### That you can add websites to your channels in MS Teams
