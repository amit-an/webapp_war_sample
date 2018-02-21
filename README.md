## Sample CI/CD using GitLab and GitLab CI:
GitLab provides various options of configuration schemes for GitLab CI on multiple perform.
For GitLab CI, Any task that need to be performed (From Compilation-build to deploy) on code is written step by step in ‘.gitlab-ci.yml’ (located on home directory of project)that is executed by a runner configured on another machine for that project.

To set up Gitlab-CI, we need to first set runner for the project. It might be shared or project specific.

 •	A ‘shell executor’ has been taken, where most of the build task will be manual (Will be taken care by maven’s pom.xml in this case) for the runner.
 •	Once configured,‘.gitlab-ci.yml’ is created in home directory of project ‘webapp_war_sample’

### Configuration of Runner and other information can be found here: https://docs.gitlab.com/runner/

## Using Secret Variable in GitLab

while writing jobs and tasks in .gitlab-ci.yml we need not to mention everything. We may abstract few things through secret variable.
For Example: Value of the variable ‘$SONAR_URL’ is specified in secret variables setting in GitLab project setting.

![elimu ai-tagline](https://user-images.githubusercontent.com/15718174/28230075-c42d3e8e-68e5-11e7-8d97-c99d9c7c322e.png)

Web application: http://elimu.ai

## Run application locally
See Wiki: [Project Configuration](https://github.com/elimu-ai/webapp/wiki/Project-Configuration)

## Contributing guidelines
See https://github.com/elimu-ai/webapp/blob/master/CONTRIBUTING.md

## Continuous integration
Travis: [![Build Status](https://travis-ci.org/elimu-ai/webapp.svg)](https://travis-ci.org/elimu-ai/webapp)

## Issue management
See https://github.com/elimu-ai/webapp/projects and https://trello.com/elimuai_public

## Chat
See http://slack.elimu.ai

## Mailing list
Sign up at http://eepurl.com/bGihkr
