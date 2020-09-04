# Python-Basics-An-Analytical-Programming-Project

The objective of this project is to produce an application and report that
allows the user to explore some of the most interesting aspects of the
IMDB dataset. The dataset is easily available on Kaggle: IMDB movie dataset. 

When runs the program it displays the following menu:

Please select one of the following options:
1. Most successful directors or actors
2. Film comparison
3. Analyse the distribution of gross earnings
4. Genre Analysis
5. Earnings
6. Exit

Description for each menu options:

<b>1. Menu Option 1 – Most successful directors or actors :</b>
When the user selects the first option (“Most successful directors or
actors”) they should be presented with the following menu.
i. Top Directors &
ii. Top Actors.
If the user selects “Top Directors” they will be asked to enter an integer
value specifying the number of directors they want to return. If, for
example, the user enters the value 10 then the ten most successful
directors (based on gross film earnings) will be outputted.
If the user selects “Top Actors” they will similarly be asked to enter the
number of actors they wish to display. If, for example, the user enter the
value 8, they will be shown the top eight most successful actors (based
on gross film earnings).

<b>2. Menu Option 2 – Film Comparison: </b>
If the user selects “Film Comparison” the code asks the user to
enter the name of two films from the dataset. The code provides basic error checking. If the user enters the name of a film not
contained in the dataset it repeatedly ask the user to enter a
valid film name.
Once the user has entered two valid film names they should be
presented with the following options.
i. IMDB Scores,
ii. Gross Earning, &
iii. Movie Facebook Like.
The user will select one of these options and the application will
display a simple bar graph comparing the two films using the option
selected.

<b>3. Menu Option 3 – Analyse the distribution of gross earnings</b>
If the user selects “Analyse the distribution of gross earnings” then the
program asks the user for a start year and then for an end year
for the analysis. Using a line graph it then display the min,
average and max gross earnings achieved by the films for each year
between the start year and end year inclusive. The line graph
have three lines, one for max, one for average and one for min.
The report contains the line graph that is outputted when the
user enters a specific start and end year.

<b>4. Menu Option 4 – Genre Analysis </b>
If the user selects “Genre Analysis” the program presents a listing
of all unique genres included in the dataset. The user then is
asked to input a specific genre and the program outputs the mean
IMDB score of all films within that genre.

<b>5. Menu Option 5 – Earnings and IMDB scores:</b>
We are interested in building a model that will predict the IMDB score of
each film with a reasonable level of accuracy. To assist in the process
we examine the relationship between the
numerical IMDB scores and other numerical columns in the dataset.
Generate graphs that will best help illustrate the relationship or lack of
relationship between the IMDB column and the other features.

<b>6. Menu Option 6 – Exit:</b>
If the user selects an option 1-5 then the program displays the
associated output and will subsequently display the main menu again.
If the user selects option 6 the application exit.
