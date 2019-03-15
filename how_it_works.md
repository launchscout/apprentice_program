## Assessment

The assessment process consists of 4 steps:

1. Initial contact

When they apply throught the website, they will get added to the candidates list in RecruiterBox. This will also trigger a reply email advising the candidate of next 3 steps.

2. Math/Logic test

This is a test designed to assess candidates for aptitude. It consists of story problems that probably involve a early HS level of math knowledge. It was borrowed with permission from boot camp in San Antonio, and is currently implemented as Google Form that feeds into a Google Spreadsheet. A rake task every 15 minutes copies the results into the Team App under the Math/Logic Results section. This screen will display the semi-automatically graded results of each student. Results start as unverified, the grading process of checking each incorrect answer to make sure it is truly incorrect. Because these are free-form text responses, there are many answers that may be deemed correct. Each answer marked as correct will be assumed to be correct if seen in future candidate responses. When a response is verified by checking Verify on the response, the percentage grade is added to the candidate profile in RecuiterBox via their API.

3. Initial coding assessment

The initial coding assessment is performed on an application they've created and submitted. I look for it to be an original app, checking for plagiarism or having followed a step by step tutorial. Sometimes apps submitted can be too simple. A few lines of javascript or an html/css website are not enough. Ideally, something that could actually be useful in some way, something that has a functional client and server, or integrates an API are all good examples. I want to see something that convinces me they can be a developer.

The assessment itself consists of them working on the app for about an hour to add a feature to it. I look for them to be able to reason about their code, be able to effectively debug. If they look something up, that is encouraged. I'll point out syntax errors or typos, and ask leading questions if they get stuck. I'll also point out things that are purely factual knowledge like null and undefined not being the same in javascript. If they don't seem to understand logic issues, or how to write code, that's a sign they aren't ready yet. If they struggle mightily with using the computer, navigating the filesystem or command line, that's also a sign to watch out for. The most important positive indicator is a subjective question: "Will this person be a good developer some day?"

4. Second coding assessment 

For the second coding assessment, we do an exercise from exercism.io. Ideally, this assessment is performed by a different mentor. We send an email to suggest they attempt a couple on their own and pick one we can do together. During the coding assessment, we look for algorithmic problem solving skills, and want to see that they know how to use exercism and grok the concept of making the tests pass. If time permits, we like to talk about how we can improve the code after getting the exercism working. The ability to problem solve, debug, and write code are the most important skills. I'll point out typos and sometimes ask leading questions but try to not to help unless they get completely stuck. Again, the key goal is for them to demonstrate that they have an understating of solving problems with code, and will be a good developer if given the chance.

5. Pre-apprenticeship

Once they complete the second coding assessment, if both go well we will inform them they are ready to join us as an apprentice. If there is a team ready for them to join, we transition them into whatever interview process (if any) exists for that client. If no interview is required by the client, we discuss timing constraints with the apprentice(s) and select a date for the apprentice team to start

## Starting an Apprentice Team

1. Starting the Mentor

Whenever possible, it is best to have the mentor start 2-4 weeks ahead of the apprentices. The mentor should be working with the team pairing with developers on stories. This gives the mentor context and specific knowledge to pass along to the apprentice. It is very helpful for the apprentice to see the mentor say "I don't know" and figure things out during the project. However, it can be overwhelming to start mentoring on a project cold and have to direct a brand new apprentice just getting started. This the time when an apprentice needs the most specific direction, and if the mentor is brand new to the team and project this is not easy to do. This transition period seeks to strike the right balance and keep the mentor just a bit ahead of the apprentices in terms of knowing what's going on.

2. Starting the apprentices

Planning out the first week(s) for the apprentices is a good idea. Here are some of the activities you'll want to include

* Any security stuff (badges)
* Laptop set up
* Meeting the team
* Overview of the project
* Mob coding an initial story

For a larger group of an apprentices in a complex technical environment, we've found it helpful to run a "mini-bootcamp" where we do coding labs in each of the technologies a project is likely to use culminating in a mock project where the team builds something utilizing as much of the stack as possible.

## Running an Apprentice Team

Here are the activities an apprentice will normally do as part of a team

### Implementing features with the team

This is the core activity we expect the apprentices to spend most of their time doing. We expect this to be mostly done via pair programming. In the beginning, it will be "mobbing" with both apprentices and the mentor. Going slowly and giving each apprentice time at the keyboard, even if they don't know what they are doing yet and are mostly taking dictation, is ok. As soon as is reasonable, this might move into 1-1 pairing with other team members. When it does, we will regularly collect feedback from other team members pairing with apprentices.

### Coding Together

Each week, we like to get all the apprentices together to see and discuss one another's code. There are several formats and mechanisms we've used to do this in the past:

* Exercism.io
  * Assign ahead and review together
  * Mob together
* "Breakable Toy" Project assigments
* Code reviews of their day to day work

### Book club

* Apprenticeship Patterns

### Weekly 1-1s

### Monthly Assessment

* Meet with members of client team to review performance of apprentices.
* Compare apprentice progress to expectations document.

## 
