# NSC Individual Practice Movie Database – EER Diagram

One key design decision was the movie_credit table. One person can join a movie
in more than one role. For example, Ben Affleck was the director, an actor, and
a producer in Argo. If the primary key were only person_id and movie_id, his
second and third roles would be duplicates and could not be saved. So the
primary key includes person_id, movie_id, and role.

My biggest challenge was deciding how tables should relate to each other, how
many tables I needed, and how deep to go. While checking data, I also found two
famous people named Steve McQueen, so I had to confirm which one was the
director.

To solve these problems, I followed the project handout, kept the design simple,
and tested my tables by thinking through 1NF, 2NF, and 3NF.

Sample data was organized with AI help and checked on Wikipedia; reviewers and
ratings are fictional.
