# Project Info

## Project Structure
After deciding on a project and getting my approval to continue, you should structure your project timeline the following way:
1. Decide what data you need and how to collect it. This will also likely mean figuring out how to label your data for supervised learning as well. You will also need to decide how your data will be stored (e.g. in a database, csv files, a directory).
2. Perform data inspection and cleaning to make sure your dataset is good enough to train on. Bad data will create bad models.
3. Run ML experiments (e.g. in Jupyter Notebook) to decide on an ML strategy, including which preprocessing, feature engineering, and ML models to use.
4. Once you decide on the right strategy from (3), you will now create a pipeline using Python scripts to implement this strategy. This should be software engineering quality code.
5. You will then design a REST API using Flask to serve your model.
6. You will also implement a working front and back end to enable users to interact with your model.
7. You will make your project a proper Python package that is installable via pip and provide documentation on its use.