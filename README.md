# Mentorship Info

## Expectations
1. Decide on a project quickly. This is what the whole mentorship will be based around. At most you should have this decided within one week of the mentorship start date. We will discuss project ideas, but you should choose something that (1) you find interesting and will keep you motivated to finish, and (2) is feasible to complete end-to-end in two months or less.

2. Barring rare exceptions, projects will be done in Python 3. It is assumed that you already have some experience coding in Python. It is also assumed that you can work with both Python script editors/IDEs, and with Jupyter Notebook.

3. If you don't already have a github account, create one. Create a new repository for your project and add me as a contributor. My username is _rkingery_. All code for the project *must* be done inside this repository, and will be expected to be version controlled using `git`. All edits must be made via branches to master, and merges can be made to master only by opening a pull request and having me code review and approve the request first.

4. If you're already applying for data science or ML jobs, decrease the frequency for now. We'll ramp this back up towards the end of the mentorship. The only ones you want to apply to are low-risk jobs that you don't care much about, so that you can practice your interview skills with little lost from doing so.

5. We will meet in person once a week via Zoom for about an hour. The goal of this meeting will be to review what you've accomplished so far, clear up any blockers or questions you have, and set goals for the next week. These "goals" and their status will be kept track of using an informal Scrum approach, either in an Excel spreadsheet or on AirTable or Trello.

6. On top of this, you will send me updates every couple days on the SM Slack channel describing what you worked on those two days along with what you will be working on the next two days.

7. Be prepared to allocate at least 10 hours per week on your project. Towards the end of the mentorship, be prepared to allocate an additional 5-10 hours per week to job application and interview prep. Unless otherwise specified, assume the mentorship will last approximately 2 months.

8. If you can't make a meeting or fulfill your goal for a sprint, you should let me know ASAP. The sooner you let me know, the sooner we can work something out. I assume you will be professional in your obligations and treat this as you would your dream job.

## Project Structure
After deciding on a project and getting my approval to continue, you should structure your project timeline the following way:
1. Decide what data you need and how to collect it. This will also likely mean figuring out how to label your data for supervised learning as well. You will also need to decide how your data will be stored (e.g. in a database, csv files, a directory).
2. Perform data inspection and cleaning to make sure your dataset is good enough to train on. Bad data will create bad models.
3. Run ML experiments in Jupyter Notebooks to decide on an ML strategy, including which preprocessing, feature engineering, and ML models to use.
4. Once you decide on the right strategy from (3), you will now create a pipeline using Python scripts to implement this strategy. This should be software engineering quality code.
5. You will then design a REST API using Flask to serve your model.
6. You will also implement a working front and back end to enable users to interact with your model.
7. You will make your project a proper Python package that is installable via pip and provide documentation on its use.

## Things You Will Learn
1. Version control and git
2. Software engineering best practices, including agile/scrum methodologies
3. Unit testing
4. Docker and containerization
5. Service oriented architectures and REST APIs
6. Basic DevOps and cloud management
7. Object-Oriented Programming in Python
8. Setting up an end-to-end ML pipeline for production
9. Code documentation best practices
10. State of the art ML in your project domain
11. How to answer interview questions about all these things
12. Continuous Integration tools
13. How to create Python packages that are pip installable
14. Just enough full-stack development to show off your project to ordinary people
