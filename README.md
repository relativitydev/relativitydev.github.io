# Relativity Development Community Home

## Add/Remove Featured Repositores
To edit the featured repositories, add/remove or update the data/featured-repos.json with the desired repository information.  Each featured repository must have an org and repository property. The org property should match the name property from one of the entries in the organizations array in the organizations.json file.  The repository property should match the name of the GitHub repository.

## Add/Remove Topics
To add a new topic, insert the topic at the end of the array in the data/topics.json file.

## Add/Remove organizations
To add a new organization, insert the organization object at the end of the array in the data/organizatiions.json file.  Each organization must have a name, GitHub organization name, and an authorType.  The name property should be the display name.  The GitHubOrgName property should be the official GitHub organization name.  The authorType property should be one of the following types: 
- kcura
- development partners
- open source community

## Source Code
The source code for this application can be found at: https://github.com/relativity-dev/relativity-dev.github.io. 


