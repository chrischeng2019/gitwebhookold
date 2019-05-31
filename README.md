# gitwebhook
Per [SDLC policy](https://gridxwiki.atlassian.net/wiki/spaces/BAC/pages/861405560/GridX+Software+Development+Life+Cycle+SDLC), the check-in comments should contains JIRA ID.The API will receive notification from github for every push action, and validate the users' check-in comments.If comments does not contain valid JIRA ID, a reminder email will be sent the code commiter.
## Build flat jar
 gradle shadowjar
 
 
 
