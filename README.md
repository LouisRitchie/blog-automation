#:construction: Automatic blogging :construction:

###Cron jobs, shell scripts, and python

I built this thing to ask me 3 questions every day:

1. How many hours did I work, how focused was I, how effective was I, and how many lines of code did I write?

2. Write a blog post based on whatever I have been doing. Probably short and opinionated but hopefully with useful details.

3. Record my desktop and show the state of whatever I'm working on. I just like webms; to be honest, I don't know about this.

This data is labelled and sent to my server when the scripts finish getting all of the above data.

After all of that is done, a cron job on the server (also in this repo) makes this data into nice pretty blog posts. That's gonna be a lot of python, probably.

###HTML sucks to write

I am pretty fucking tired of writing HTML. I never want to write any HTML outside of JSX ever again. That is the motivation for this.

###Templating language for something this small?

No thanks. I'm gonna hand-write a bunch of python that can parse my data and produce HTML that nginx can point to. That way I don't have 
excess and then the entire process of data entry to polished blog output is 100% hand made, which is nice.


