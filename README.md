# iPhone Automation

Contains iPhone [Pythonista](http://omz-software.com/pythonista/docs/) scripts for iPhone automation.

## First Time Setup
1. Set git remote head to development: 
```bash
git remote set-head origin development
```
2. Update your .vscode/settings.json colors to be different from your other workspaces. Use [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock) to change your colors easily.

## Project Automation and Dev Ops

1. **Issue Templates** - Default created issue templates
    1. _Bug Report_ - Create a bug report issue
    2. _Feature Request_ - Create feature request/enhancement
    3. _Dev Ops Request_ - Create a new development operations request, this can be sever management, user access item, workflow automation enhancement, or a report of issues going on with cloud infrastructure
2. **Workflow**
    1. _Auto Assign Issue to Project_ - Will link a project whenever a new issue is created and whenever a pull-request is made in master or development,links to: [iPhone Automation Improvement Project](https://github.com/Cassio-is-Great/iphone-automation/projects/1).
    2. _Auto Assign_ - Using [Auto Assign](https://github.com/apps/auto-assign) (must be added to your organization or GitHub user) this repos default behavior is for it to assign the creator of a pull request to the author of the pull request

## Deployments
Code deployment is currently not in a great state. Currently the deploy path can **only** be ran locally using custom bash scripts: 
```bash
ipar
```
This will run this: `git -C "/Users/cassiohudson/Library/Mobile Documents/iCloud~com~omz-software~Pythonista3/Documents" pull origin master` 

### Created by:
[Cassio Hudson](https://github.com/Cassioblu55)
