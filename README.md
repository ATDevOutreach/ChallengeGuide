# A Guide to Creating Your Next Code Challenge -- clone and edit as needed
#### Remember to delete the .git files before pushing new version, if working from this version.

 You can use this guide for creating consistent code challenges across the board.

 ### Step 1: Folder
- Create a folder where your code challenge will live. 
- For clarity[Optional] name your folder in the format<CodeChallenge><TargetAudience><Date><Month><Year>: e.g CodeChallengeUniBen23062018
- In the folder create a README.md file and a docs folder

### Step 2: Folder Contents
##### README Introduction
- Create the introduction information as follows: 
- H1 Code Challenge Topic and the Audience e.g. 2 Way SMS Code Challenge: University of Benin - Benin City
- H2 The Due Date e.g. Due: 17th June,2018 or Earlier
- H3 Any other information or emphasis e.g. This code challenge is due on the 17th of June,2018 or earlier. 

##### README Rules, Terms and Conditions
- These have been confirmed by the legal team and can remain as is: example below.

###### Simple Unchanging Rules
The code challenge is and will always be judged using the following criteria
  - A Correct fork, branch and pull request
  - Using the GitHub Pull Request Time Stamp and correct code quality & structure, the first developer whose code runs successfully on the sandbox/simulator wins
  - Other developers who submit successfully MAY also get rewarded with secondary items
  - Code quality and structure will be evaluated
  - The order for pull requests will be followed, first come first win basis!
  - Do not share any code that you cannot opensource on the Git Repository as its open source and Africa's Talking will not be liable for any breach of intellectual property (if any) once shared on the platform.

###### Terms and Conditions
You can participate on as many challenges as you wish:
  - Everyone can participate for secondary prices, just ensure that you create your branch with your international format phone number. Airtime rewards will only go to countries we have AirTime APIs in.
  - Africa's Talking reserves the right to announce the winners
  - Africa's Talking reserves the right to reward the winners based on Africa's Talking Criterion
  - Do not share any code that you cannot opensource on the Git Repository as its open source and Africa's Talking will not be liable for any breach of intellectual property (if any) once shared on the platform.
  - Code Challenges are time bound - the time restriction is specified on the challenge
  - Additional rules MAY be provided on the code challenge and will vary for each challenge
  - You are free to use all manner of tools
  - Successive interviews for projects MAY be run to satisfy participating Africa's Talking Partners

##### README Code Challenge Bounty
Update the boundy based on your audience. Basically the levels of prices are two:
- Level 1 [The Main Prize]: The first number of people(1 or more) to submit the working code, based on the Git timestamps
- Level 2 [The Secondary Prize/Airtime]: Everyone who submitted working code before the deadline. 

##### README Task
An explanation of the task to be accomplished with the cod challenge. e.g. <br>"In this code challenge you should create a 2-way SMS app that can be accessed on the Sandbox. The 2-Way SMS App should allow users to send an SMS from their simulator to your short code, and get a simple reply."

##### README Task Workflow: 
This section outlines the user journey of the app to be built. Here is an example.
1. User ends an SMS with any content text.
2. You Short code App responds with the Message: "I am a fisherman. I sleep all day and work all night!"
3. Add to the README.md a small guide of how to access your serive on the Simulator.
4. Ensure your service is accessible online. You can use the free tiers of [Heroku](https://www.heroku.com/) or [Openshift](https://www.openshift.com/) or other platform of choice.

##### README Additional: [Optional]
Place all other resources that accompany the explanation of the code challenge. In this case we are using viewdocs.io to render a copy of the .md files in the docs folder online.
###### How viewdocs.io works
- In the repo with the README.md, make a directory called docs.
- In the docs directory, create at least one file index.md that viewdocs.io looks for and publishes. Other files in docs will also be published in their own paths. e.g. in a repo codeChallenge2010, having a docs folder containing introduction.md, index.md and about.md, with username famousdeveloper, on pushing the repo, the files can be accessed as follows:
1. index.md : http://famousdeveloper.viewdocs.io/codeChallenge2010/
2. introduction.md : http://famousdeveloper.viewdocs.io/codeChallenge2010/introduction
3. about.md : http://famousdeveloper.viewdocs.io/codeChallenge2010/about

##### README Resources
Place all the resources that the developer can use to get started and successfully conclude the challenge. These can be:
- Tutorials 
- AT Docs
- AT Help Center, etc.
See the example below. <br>

You can use the following resources to get you started on your way:
* [Starting on the Sandbox and Simulator](http://help.africastalking.com/website/how-to-get-started-on-the-africas-talking-sand-box)
* [SMS Sending Documentation](http://docs.africastalking.com/sms/sending)
* [SMS Receiving Documentation](http://docs.africastalking.com/sms/callback)
* [Other SMS Help articles](http://help.africastalking.com/sms)
- More on [Logging in, Signing up/Registration, Verifying/Activating your account, Managing Teams and applications](http://help.africastalking.com/website)
- Videos on getting started [on the Africa's Talking Sandbox](https://www.dropbox.com/sh/qq086503d5zaq7l/AADEo-oazNF_PgYIPRjPpeCua?dl=0)


##### README About Africa's Talking Code Challenges
You can place more information about the code challenge by AT in the docs folder. The URL will be different in your case e.g.<br>
Please read the overview for all code challenges [here.](http://atdevoutreach.viewdocs.io/CodeChallengeUniBen1606/)

##### README Get Support on the Africa's Talking Slack
Direct the audience to the AT Slack.<br>
In case you have any questions, join our Slack [here](https://slackin-africastalking.now.sh/)

### Step 3: /docs Folder
Within the docs folder in your repo is where all the .md files that you want to be visible via viewdocs are made available. Most important is the Code Challenge Steps which guide the audience on how they submit their solution to the code challenge.
##### /docs ChallengeSteps.md 
You can rename this file. This file indicated the steps required to submit the solution to the challenge.
##### /docs ChallengeGuide.md
You can rename this file. This file is the viewdocs version of the code Challenge
##### /docs index.md
You CANNOT RENAME this file. This curently holds the information about Africa's Talking and our thinking on the code challenges.

