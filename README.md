# Six_degrees_of_Kevin_Bacon
According to the Six Degrees of Kevin Bacon game, anyone in the Hollywood film industry can be connected to Kevin Bacon within six steps, where each step consists of finding a film that two actors both starred in. This program determines how many “degrees of separation” apart two actors are.
We use Artificial Intelligence Search Methods For Problem Solving, for this program to behave in an intelligent manner to be able to solve problems. Hence this program effectively is able to arrive at decisions that transform a given situation into a desired or goal situation. This is implemented in the degrees.py life in the shortest_path function.

The distribution code contains CSV data files in the large directory.
In large/people.csv each person has a unique id, corresponding with their id in IMDb’s database. They also have a name, and a birth year.
In large/movies.csv each movie also has a unique id, in addition to a title and the year in which the movie was released.
In large/stars.csv relationship between the people in people.csv and the movies in movies.csv. Hence each row is a pair of a person_id value and movie_id value. 
