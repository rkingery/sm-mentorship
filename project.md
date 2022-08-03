# Project Plan

## Project Statement
- What is the problem you're trying to solve and why?
- How is this problem being solved now?
- How will you improve on this solution?

## Success Metrics
- How will project success be measured, i.e. how do we know when we're "done"?
- Assuming we have defined a success metric that can clearly be used to measure success, what will it mean for your solution “good enough”?
- What should the threshold of success be? That is, what threshold should your success metric reach for you to declare success?
- What factors are important for project success?

## In Scope
- What things must this project definitely tackle to be successful?
- What questions must still be answered as we go?
- What problems *must* be solved to successfully finish the project?
- What technologies are available for use to do the project?

## Out of Scope
- What things must the project definitely not tackle?
- What things are "nice to haves", but definitely not "essential" to solve the problem you defined above?

## Risks
- What barriers do you currently see to project success, i.e. the ability to meet the above success criteria in the allotted time?

## Open Questions
- What questions still need to be answered as the project goes on that may hinder success?

## Schedule Overview
- We will have 1-week sprints. Note a "sprint" is just a cycle of work which together make up a project.
- Sprint planning will be on Monday via Zoom, time about 1 hour.
- Daily standups (DSUs) will be every other day, via Slack. Tentatively, if planning is Mon, DSUs will be Wed, Fri, Sun. Each DSU should always address the following 3 questions:
	- What did I work on this time?
	- What will I work on next time?
	- What blockers (if any) do I have? Note blockers are situations hindering your ability to keep pace and need resolved to move forward
- At the end of sprints we will have retrospectives, which will be done combined with the planning session for the next sprint. Maybe 5-10 mins at start of meeting.
	- What was learned during sprint, good or bad?
	- What lingering issues are left from the last sprint?
- Each sprint will have a list of tasks that we mutually decide on, and your goal each sprint is to complete all of those tasks.
- Project will also be divided into epochs (e.g. data collection and cleaning, experiments, software creation, deployment, etc).
- We will use [Trello](https://trello.com/) to keep track of all mentorship-related work. You will be expected to manage each of your tasks in Trello.
- All direct communications with me will be done via my own SM Slack [here](https://rkingerysmmen-lsg5457.slack.com/). Note I must add you to this Slack for you to participate. Only mentees will be added.

## Example Timeline
1. Sprint 1: Exploratory data analysis / baseline model experiments
2. Sprint 2: Data cleaning / feature engineering
3. Sprint 3: Improve on baseline models
4. Sprint 4: Finalize improvements model improvements
5. Sprint 5: Convert experimental results to software code and write unit tests
6. Sprint 6: Containerize and deploy backend
7. Sprint 7: Create fully functional python package
8. Sprint 8: Implement front end / Deploy software

## Example Project Workflow
After deciding on a project and getting my approval to continue, you should structure your project timeline the following way:
1. Decide what data you need and how to collect it. This will also likely mean figuring out how to label your data for supervised learning as well. You will also need to decide how your data will be stored (e.g. in a database, csv files, a directory).
2. Perform data inspection and cleaning to make sure your dataset is good enough to train on. Bad data will create bad models.
3. Run ML experiments (e.g. in Jupyter Notebook) to decide on an ML strategy, including which preprocessing, feature engineering, and ML models to use.
4. Once you decide on the right strategy from (3), you will now create a pipeline using Python scripts to implement this strategy. This should be software engineering quality code.
5. You will then design a REST API using Flask to serve your model.
6. You will also implement a working front and back end to enable users to interact with your model.
7. You will make your project a proper Python package that is installable via pip and provide documentation on its use.
