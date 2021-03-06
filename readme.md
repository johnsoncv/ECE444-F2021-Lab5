# Cansin Varol

# This   repo   is   a   clone   of https://github.com/nelaturuk/education_pathways.

# Activity 1
<img width="1464" alt="Screen Shot 2021-10-17 at 17 38 47" src="https://user-images.githubusercontent.com/48742114/137645901-9a6b6ad4-e3b8-4ef6-9e37-d61255f3f237.png">

# Activities 2-5
<img width="1664" alt="Screen Shot 2021-10-17 at 20 13 04" src="https://user-images.githubusercontent.com/48742114/137650487-25c912ef-f9d3-4bca-a5dd-6f8a86950b9f.png">

<img width="1648" alt="Screen Shot 2021-10-17 at 20 18 52" src="https://user-images.githubusercontent.com/48742114/137650489-e3c44180-4863-4a20-af20-6d5e43fe02ab.png">

<img width="1664" alt="Screen Shot 2021-10-17 at 20 18 32" src="https://user-images.githubusercontent.com/48742114/137650492-57a9dc00-731a-4ad0-89ca-3bc1514cf33a.png">

# Activity 6
The new styled UI uses borders which clearly separates the results and makes it easier for the user to view them. The additional "Search Results" section also separates the results from the search form which clearly represents the results data. The clear separation between the columns also makes the page more easily readible.

# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
