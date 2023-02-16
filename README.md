# navex-esg-frontend-ui
## Environments / CodePipelines for each branch

Lab/Dev
- [Lab/Dev](https://lab.navex-int.com/esg/)

Wobbly
- (https://csrtenant.id3.wobbly.navex-int.com/auth/realms/master/protocol/openid-connect/auth?client_id=security-admin-console)


CodePipelines
- [Team City - Build](http://10.64.111.236:8112/login.html)
- [Octopus - Deployment](http://clt-dv-octopus1.yoda.local/app#/Spaces-1/projects)

## Process
Builds will be ran on Pull Request creation and commit push, and merging code will require all pre-requisites to pass.


## Installation
Pull down the `develop` branch from `https://github.com/tnwinc/navex-esg-frontend-ui` repository.
	
## Branching
The `navex-esg-frontend-ui` repository uses a "feature" branch based method of code branching. All branches should be based off `release/*`, and return to that release branch upon story completion.

The process ends up as such:
1. Create feature branch off release.
2. Locally develop and commit to that branch until completion.
3. Push branch out into `develop` environments to dev.
4. Create PR for branch to go into `release/*` branch.

## Front End Development

Please flow the below steps for front setup,
`npm install` This command installs a package and any other dependent packages. 
`npm run start:development` Runs the app in the development mode.
                            Open https://lab.navex-int.com/esg/ to view it in your browser.


