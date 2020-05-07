In this in class assignment, you’ll practice your newfound SQL chops. Please “show your work” by copying and pasting in the SQL statements you used to provide your answer. For example, if we ask “how many genes are there in homo_sapiens_core_98_38?” then your answer might look like this:
mysql> SELECT COUNT(*) FROM gene; +----------+
| COUNT(*) |
+----------+
      |    67946 |
      +----------+
Please be kind to your instructors and use a fixed width font for your answers!
1) How many human transcripts were in Ensembl version 48? 58? 68? 78? 88? 98? For this one, please just provide one sample SQL query, and then list your answers/numbers in a list format.
2) What does the acronym ‘SQL’ stand for?
3) In homo_sapiens_core_98_38:
a. How many karyotypes are there?
b. How many unique karyotype stainings are there? Provide both a count and a list.
4) In homo_sapiens_core_98_38, how many genes have a stable ID that begins with
“ENSG000002” ?
5) How many distinct biotypes are there for human genes?
6) Optional: Create a new question to pass along to next year’s cohort, hopefully
something with a nasty JOIN.
