# Desk Buddy



## Getting started

To make it easy for you to get started with GitLab, here's a list of recommended next steps.

Already a pro? Just edit this README.md and make it your own. Want to make it easy? [Use the template at the bottom](#editing-this-readme)!

## Add your files

- [ ] [Create](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#create-a-file) or [upload](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#upload-a-file) files
- [ ] [Add files using the command line](https://docs.gitlab.com/ee/gitlab-basics/add-file.html#add-a-file-using-the-command-line) or push an existing Git repository with the following command:

```
cd existing_repo
git remote add origin https://git.chalmers.se/courses/dit113/2023/group-8/desk-buddy.git
git branch -M main
git push -uf origin main
```

## Integrate with your tools

- [ ] [Set up project integrations](https://git.chalmers.se/courses/dit113/2023/group-8/desk-buddy/-/settings/integrations)

## Collaborate with your team

- [ ] [Invite team members and collaborators](https://docs.gitlab.com/ee/user/project/members/)
- [ ] [Create a new merge request](https://docs.gitlab.com/ee/user/project/merge_requests/creating_merge_requests.html)
- [ ] [Automatically close issues from merge requests](https://docs.gitlab.com/ee/user/project/issues/managing_issues.html#closing-issues-automatically)
- [ ] [Enable merge request approvals](https://docs.gitlab.com/ee/user/project/merge_requests/approvals/)
- [ ] [Automatically merge when pipeline succeeds](https://docs.gitlab.com/ee/user/project/merge_requests/merge_when_pipeline_succeeds.html)

## Test and Deploy

Use the built-in continuous integration in GitLab.

- [ ] [Get started with GitLab CI/CD](https://docs.gitlab.com/ee/ci/quick_start/index.html)
- [ ] [Analyze your code for known vulnerabilities with Static Application Security Testing(SAST)](https://docs.gitlab.com/ee/user/application_security/sast/)
- [ ] [Deploy to Kubernetes, Amazon EC2, or Amazon ECS using Auto Deploy](https://docs.gitlab.com/ee/topics/autodevops/requirements.html)
- [ ] [Use pull-based deployments for improved Kubernetes management](https://docs.gitlab.com/ee/user/clusters/agent/)
- [ ] [Set up protected environments](https://docs.gitlab.com/ee/ci/environments/protected_environments.html)

***

# Editing this README

When you're ready to make this README your own, just edit this file and use the handy template below (or feel free to structure it however you want - this is just a starting point!). Thank you to [makeareadme.com](https://www.makeareadme.com/) for this template.

## Suggestions for a good README
Every project is different, so consider which of these sections apply to yours. The sections used in the template are suggestions for most open source projects. Also keep in mind that while a README can be too long and detailed, too long is better than too short. If you think your README is too long, consider utilizing another form of documentation rather than cutting out information.

## Name
Desk Buddy

## Description
The goal of this project is to build a “desk aid” system using Arduino technology and a Wio Seeed Terminal. The system makes sure desk workers who spend a lot of time sitting still work in a healthy environment, stay hydrated and get regular physical movement. 
The system utilises multiple sensors to measure and monitor temperature, humidity and other environmental factors. The results of these measurements are communicated to the user via a summary of the overall environment conditions. The user is notified on the status of the overall environment values in the form of a “smiley face” which is either happy or sad depending on if the environment goals are met. The user will recieve reminders to stretch and to hydrate regularly. Furthermore the user will recieve motivational quotes auditoraly. 
The system has options for preference settings regarding time intervals, sensitivity of sensors etc. which is customizable by the user through a system phone app.

## Badges
// TO-DO

On some READMEs, you may see small images that convey metadata, such as whether or not all the tests are passing for the project. You can use Shields to add some to your README. Many services also have instructions for adding a badge.

## Visuals
// TO-DO

Depending on what you are making, it can be a good idea to include screenshots or even a video (you'll frequently see GIFs rather than actual videos). Tools like ttygif can help, but check out Asciinema for a more sophisticated method.

## Installation


To be able to use this system, you need a [Wio Terminal](https://www.seeedstudio.com/Wio-Terminal-p-4509.html) and the following sensors:

1. [Grove - Multi Color Flash LED (5mm)](https://www.seeedstudio.com/Grove-Multi-Color-Flash-LED-5mm.html)
2. [Grove - Button](https://wiki.seeedstudio.com/Grove-Button/)
3. [Grove - Light Sensor v1.2](https://wiki.seeedstudio.com/Grove-Light_Sensor/)
4. [Grove - Speaker](https://wiki.seeedstudio.com/Grove-Speaker/)
5. [Grove - Temperature & Humidity Sensor (DHT11)](https://wiki.seeedstudio.com/Grove-TemperatureAndHumidity_Sensor/)

For further information on installation please see the [installation wiki page](https://git.chalmers.se/courses/dit113/2023/group-8/desk-buddy/-/wikis/Installation/guides-and-installation)

## Usage
// TO-DO

Use examples liberally, and show the expected output if you can. It's helpful to have inline the smallest example of usage that you can demonstrate, while providing links to more sophisticated examples if they are too long to reasonably include in the README.

## Support
// TO-DO

Tell people where they can go to for help. It can be any combination of an issue tracker, a chat room, an email address, etc.

## Roadmap
// TO-DO

If you have ideas for releases in the future, it is a good idea to list them in the README.

## Contributing
// TO-DO

State if you are open to contributions and what your requirements are for accepting them.

For people who want to make changes to your project, it's helpful to have some documentation on how to get started. Perhaps there is a script that they should run or some environment variables that they need to set. Make these steps explicit. These instructions could also be useful to your future self.

You can also document commands to lint the code or run tests. These steps help to ensure high code quality and reduce the likelihood that the changes inadvertently break something. Having instructions for running tests is especially helpful if it requires external setup, such as starting a Selenium server for testing in a browser.

## Authors and acknowledgment
- [Karl Eriksson](https://git.chalmers.se/kaeriks)
- [Malte Bengtsson](https://git.chalmers.se/bmalte)
- [Ahmad Haj Ahmad](https://git.chalmers.se/haja)
- [Nasit Vurgun](https://git.chalmers.se/nasit)
- [Joel Celén](https://git.chalmers.se/joelcel)
- [Rizwan Rafiq](https://git.chalmers.se/rizwanra)

Show your appreciation to those who have contributed to the project.

## License
// TO-DO

For open source projects, say how it is licensed.

## Project status
// TO-DO

If you have run out of energy or time for your project, put a note at the top of the README saying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.
