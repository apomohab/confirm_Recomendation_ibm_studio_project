RECOMMENDATIONS WITH IBM WATSON STUDIO
------------------------------------------
For this project you will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like. Below you can see an example of what the dashboard could look like displaying articles on the IBM Watson Platform.


Aims
----------------------
The project will be divided into the following tasks

 - I. Exploratory Data Analysis
 - II. Rank Based Recommendations
 - III. User-User Based Collaborative Filtering
 - IV. Content Based Recommendations (EXTRA - NOT REQUIRED)
 - V. Matrix Factorization


File Structure
----------------------
* `Recommendations_with_IBM.ipynb` is the solution file

* `top_5.p`: pickle file to test top 5 rank based recommendations
* `top_10.p`: pickle file to test top 10 rank based recommendations
* `top_20.p`: pickle file to test top 20 rank based recommendations
* `user_item_matrix.p`: pickle file to load the user_item matrix
* `data` folder contains the following:
  * `articles_community.csv`: csv file containing the articles
  * `user-item-interactions.csv`: csv file containing user interactions with articles
    * `index.html`: Renders homepage
    * `go.html`: Renders the message classifier
  * `run.py`: Defines the app routes

* `tests` folder contains the following:
    *  `project_tests.py`: contains the unit tests for the solution

* It is recommended you run the solution from a jupyter notebook. Please visit
https://jupyter.org/install for installation guide.

INSTALLATION
----------------------
### Clone Repo

* Clone this repo to your computer.
* For mac please ensure you have xcode or download it from the app store (probably not needed)
* Check jupyter is installed correctly using `jupyter --version` and this should return jupyter version
* `cd` to the location of the project home directory
* Execute `Recommendations_with_IBM.ipynb`


