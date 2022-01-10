# Setting Up Your Computer

Welcome to day 1 at BloomTech, today we are going to spend time setting up your computer and learning the tools that you will be using to complete this program. Just like day 1 at a job, you will need to get your environment set up to build and run your code. Complete the set up tasks below and then get started on the research questions. Once you have finished check out the submission instructions in the `README.md` file to turn in your assignment for the day. 

## Set Up Tasks 
1. [x] [Download xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12) - these are your developer tools for mac 
2. [x] sign up for a [GitHub account](https://github.com/join) - please use a professional username. We recommending using your `firstname` `lastname`
3. [x] [Set up your SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) - GitHub uses SSH to keep their files secure. You will need to set up one SSH key for every computer that you want to access your GitHub account on. Please ensure you go through all of the steps to generate a new key, add a new key and test your connection.
4. [x] [Download Zoom](https://zoom.us/download) - make sure your zoom display name is your `first name` `last name`
5. [x] [Download Slack](https://slack.com/help/articles/207677868-Download-Slack-for-Mac) - make sure your slack display name is your `first name` `last name` 
6. [x] [Download VS code](https://code.visualstudio.com/download) - this will be the tool you use to write all of your code. We recommend installing the following extensions: 
- [ES Lint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
7. [ ] [Download Node.JS](https://nodejs.org/en/) - Please download the latest stable version. We will be using Node.JS to run the tests in all of our javaScript assignments. Test driven development is a common practice in the world of web dev. You can read more about it [here](https://www.freecodecamp.org/news/test-driven-development-what-it-is-and-what-it-is-not-41fa6bca02a2/) 
8. [ ] Sign up for a free [codepen account](https://codepen.io/accounts/signup/user/free)
9. [ ] Sign up for a free account on [Lucid Chart](https://www.lucidchart.com/pages/landing?utm_source=google&utm_medium=cpc&utm_campaign[…]tTwOoXp_lCeLTC97pikTFa5cE58FWHwjjpTSGsGPRqR2AAaAh-MEALw_wcB)

## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You can type your answer below the questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en) doc short for documentation are the instructions on how to use a languge, or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your google skills. 

1. What is git? What is the difference between git and GitHub?
Git is an open source distributed version control system-- meaning it can be used for the original source code can be redistributed and modified, can be used to store content, can maintain a history of any changes we make to that content, and has two versions where the code is stored(remote and local). The difference between Git and GitHub is that GitHub is a cloud-based server in which you can access git repositories, while Git is a system where you can modify and keep track of code history.

2. Why do we create a branch? 
We create a branch in order to keep our work isolated when wanting to make changes to code. This is to keep any experimental work separated from the 'main' repository.

3. What is the purpose of a pull request? 
The purpose of a pull request is to let your team know that there is new content pushed to a branch in the repository that needs to be reviewed, and if accepted can then eventually be merged.

4. What is the command you can use to switch between branches? For example you are working on a feature branch and you want to switch back to main. 
You would use the 'checkout' command.

5. Explain the difference between `git fetch`, `git merge` and `git pull` what does each command do? 
'git fetch' is used to check if there any changes in the remote repo but does not make any changes to the local repo, while 'git merge' is used to combine changes from branches. 'git pull' is a combination of the previous two; it runs a 'git fetch' and then a 'git merge'.

6. What is a merge conflict? How do you resolve a merge conflict? 
A merge conflict happens when changes are made to same line of a file and that content clashes. There are different ways to resolve merge conflict. One of the ways is to use a text editor. In here you will navigate to the file that has the conflicts. Next you will essentially choose which branch's changes you want to keep, yours or the other branch. You also have the option to create a new change which can include changes from both branches. After this you will add and commit your changes to the local repo.