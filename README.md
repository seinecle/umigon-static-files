# Lexicons and localized texts for Umigon (sentiment analysis)

I moved the static text files containing lexicons and localized texts, which are both used by Umigon, the sentiment analysis function.

The reason for this move was to facilitate tests. When the files were containing as resource files in different Java apps, testing functions leveraging these files was kind of complex.
As static files sitting outside apps, the difficulty is removed.

An additional expected bonus is that the apps become all the more light without these files. That should reduce their build time.

Inconvenience: as static files I am not sure I can use the NetBeans properties editor to handle them. This editor is great to explore and work with localized texts so I'll see how it goes.