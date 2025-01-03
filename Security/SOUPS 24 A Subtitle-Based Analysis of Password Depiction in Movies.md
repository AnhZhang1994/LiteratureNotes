# Batman Hacked My Password: A Subtitle-Based Analysis of Password Depiction in Movies

**Link:** [https://www.usenix.org/conference/soups2024/presentation/raphael](https://www.usenix.org/conference/soups2024/presentation/raphael)

**Conference:** SOUPS 2024

**Keywords:** Usable Security, Passwords, Movies, Subtitles

**Supplement:** https://www.itsec.uni-hannover.de/de/usec/forschung/medien/password-depiction-in-movies#c89784

### Summary

People learn knowledge from movies, influencing their perceptions about cybersecurity including heir mindset about passwords.

### Data & Methods
[Torrents from Reddit r/DataHoarder](https://www.reddit.com/r/DataHoarder/comments/w7sgcz/5719123_subtitles_from_opensubtitlesorg/). The torrent contains a database (opensubs.db, 136.8 GB) of 5,719,123 subtitle files, crawled on July 24, 2022. It also contains a metadata file (subtitles_all.txt.gz, 309 MB) that includes information such as movie name, year, language, content type (movie, TV show), season, episode, IDs (IMDB, OpenSubti- tle), upload date, frame rate, and file format.

After filtering out non-English and non-movie subtitles, resulting in 97,709 movies' subtitles and metadata.

Keyword search: Password. 9 lines before and after the keyword (That said, 19 lines in total). 5,982 scenes in total

Qualitativly analyze 50 scenes by 2 authors with MaxQDA.

Analyze Password Topics and Password Attacks

Record all passwords in the subtitles and measure their strength using zxcvbn and Password Guessability Service (PGS).

Compare their strength with The Popular-200 (200 most used passwords of 2023), The Ignis 1M wordlist, and A list from the RockYou data breach.

Watch part of 21 moives to get deeper qualitative insights.


### Results 
Types of password-contained movies, password behavior in movie scenes, password life cycle, password sharing, and Security Best Practices.

### Depiction of Password Attacks
Password guessing, where a human actively guesses candidate password based on frequent passwords, specific knowledge about a person known old passwords. (220 cases)
Password hacking, where other techniques are used to obtain the password such as social engineering or shoulder surfing or using automated tools for (brute-force) guessing. (63 cases)


### My personal thoughts
#### Pros
Leverage data from an unexpected source (movie subtitles) to analyze a real world problem (password)
#### Cons
The logics of relecting password-related behavior in movies to real-world behavior is not so concrete.
Qualitative analysis is kinda subjective and may not be generalizable.