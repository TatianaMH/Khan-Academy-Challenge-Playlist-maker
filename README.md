# Khan-Academy-Challenge-Playlist-maker

[Finished Project](https://www.khanacademy.org/computer-programming/spin-off-of-challenge-playlist-maker/6686935445979136)


**STEP ONE Khan is asking me to filter out just the songs by "Queen" by title alone**
SELECT title FROM songs WHERE artist = "Queen"

**STEP TWO Khan is asking to select the name of all of the artists from the 'Pop' genre.**
SELECT name FROM artists WHERE genre = "Pop";

**STEP THREE Khan is asking "add another query that will select the title of all the songs from the 'Pop' artists. It should use IN on a nested subquery that's based on your previous query."**
SELECT title FROM songs WHERE artist IN ("Taylor Swift", "Celine Dion", "Rihanna", "Gloria Estefan"); 

