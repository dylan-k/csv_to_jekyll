

Turn a Spreadsheet into Jekyll Markdown Files
=============================================


Have a client or a non-developer prep a bunch of content collaboritavely in Google Docs, then turn each row into a different page on a Jekyll Site easily.

I was able to take this script that turned a CSV file into a series of YAML files which did most of the work here (thanks!). I modified it a bit to create Markdown files with YAML front matter, perfect for Jekyll pages (or posts).

You can prep content in a spreadsheet 

Afterwords, export the spreadsheet as a CSV and name it data.csv.

Download the script csv_to_yaml.py here https://raw.githubusercontent.com/EvanLovely/csv_to_jekyll/master/csv_to_jekyll.py

Put the two files in the same directory, then run python csv_to_yaml.py.

This project is up on my GitHub page for anybody curious.
https://github.com/EvanLovely/csv_to_jekyll

There isn't currently a way to have the body (content) exported this way, it was originally made to get a bunch of meta-data onto a ton of files, which they'd add content to later. I could see it being done, so if you need that specifically, hit me up and I'll see if I can put it together.



a similar method: http://lou.pe/blog/converting-csv-tables-to-markdown-files