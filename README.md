# spider-web-crawler
general.py

-created function to make a directory

-created a function to add two text file to this directory (queue.text,crawled.text)

-created a function to write the data into queue file then to crawled

-created a function to delete the data of queue file after everything is crawled

-created a function to gather the data into a set (so that for every link the program does not store to file,rather make a set of data and store it at a time.To speed up the things)

-created a function to store sets into file
link_finder.py

-created a program that finds all the links in the source code of a web page and bring them to us(using predefined python function HTMLParser)

spider.py

-created the first spider by giving the domain name, project name, base url

-first spider crawls the homepage to get all the links.Then depending on the number of links, number of spiders are created to simultaneously process all the links at a time
