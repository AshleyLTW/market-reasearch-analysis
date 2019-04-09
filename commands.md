# Set-up
.headers on
.mode column

# Basics
Get beginners: 
- SELECT email FROM data WHERE level_begin = 'TRUE';

Count number of beginners:
- SELECT COUNT(email) FROM data WHERE level_begin = 'TRUE';

Get the feelings of fluent ppl:
SELECT COUNT(email), reading_feeling FROM data WHERE level_fluent = 'TRUE' GROUP BY reading_feeling;