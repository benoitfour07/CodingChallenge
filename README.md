# CodingChallenge

1) Before running the program make sure you have all librairies installed on your compture (especially the newspaper library:
http://newspaper.readthedocs.io/en/latest/user_guide/install.html

2) Then it's easy to use: just run the python code in your computer and see what happened.

NOTES:

1) I was not very usual with scrapy framework that's why I didn't use it
=> I started some tutorial but I didn't succeed in doing what I wanted to do (getting all href links for a news website homepage)
and I did it easily with newspaper

2) Articles are parsed with beautifulsoup to get back: title, subtitle, description using h1, h2 and p html parts

3) Everything is saved under sqlite databased

4) Then we look up for your keywords in the database. Here we only look into titles but we can easily extend it to the description as well.

IMPROVEMENTS:

If I could have more time I would have:
1) Try to go deeper with scrapy
2)Extend my program so we can do that on any news website. I wanted that the user enter the news website url as well.
I was closed to it but I got a lot of errors, I started fixing some of thems with try/catch but as all news website are not build on the same html
format I would have need more time to find a global parsing solution
3) I didn't really understand the CLEANSE part in the project so I didn't look into it.

THANKS!
