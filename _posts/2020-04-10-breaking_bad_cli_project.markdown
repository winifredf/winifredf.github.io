---
layout: post
title:      "Breaking Bad CLI Project"
date:       2020-04-10 09:53:23 -0400
permalink:  breaking_bad_cli_project
---


Completing this project was a bit intimidating at first.  However, after completing the CLI project, I’ve grown in the area 
of reading error messages, and I am much more confident in solving them.  Understanding how to read and solve error 
messages is a pivotal part of becoming a Software Engineer!  Being able to read and decipher error messages 
properly, while also seeking answers via Google, Rubygems.org, and other websites, was the second most rewarding 
thing I’ve gotten from completing this project!  The most rewarding, of course, was seeing my CLI project operate as it 
should!


It took me a while to decide what topic I wanted to use to build my CLI project.  It is suggested that students choose a 
topic that we are interested in.  I didn’t choose a topic I was interested in, per se.  I chose a topic that was connected to 
a meaningful family moment.  I chose a topic that I ultimately settled on the movie series, “Breaking Bad.”  Oddly 
enough, the series had significance to my children and me.  My late husband used to love watching Breaking Bad, and 
my 13 years old son reminded me during one of our conversations about dad.  I then had to decide if I wanted to 
scrape a website, or find an API to use.  Honestly, I hadn’t utilized an API prior to this project, although I have watched 
tutorials.  I have had experience scraping websites, but I can’t say scraping is a favorite of mine.  Thankfully, I found an 
open and interactive Breaking Bad API!  Yay!


[(https://)www.breakingbadapi.com/documentation]


I clicked ‘get all characters’, to narrow down my search topic, as I wanted to focus on getting all of the Breaking Bad 
characters and information.  


[https://www.breakingbadapi.com/documentation /api/characters]


Unfortunately, I could not set up Atom before beginning my CLI project as I’d lost quite a bit of time due to a medical 
emergency that required surgery.  The Learn IDE presented its challenges, but nothing I could not overcome!  I quickly 
learned that with the Learn IDE, two of my gems, ‘pry,’ and ‘rest-client,’ had to be installed each time.  These two gems 
did not load with the other gems at start up, and therefore I had to gem install each of them every time.
Creating and coding my api.rb, cli.rb, characters.rb, in my lib folder, and my breaking_bad_project_cli_character_finder 
in my bin folder had it’s hiccups.  I was actually fine until the my very last method I’d created ‘get_character_details’.  My 
greeting, list of characters, and user input worked as they should.  However, when the user keyed in a number, it would 
return all the characters and details.  It turned out that I didn’t have my char and input variables in the right place in my 
cli.rb file, as well as my self.find method in my characters.rb file.  After correcting, everything worked as it should, and 
returned the proper number when requested by the user instead of all characters and their details!  Whew!
Getting through the first project was a great challenge.  Having to apply everything I’ve learned thus far on my own was 
scary.  I liken it to FlatIron saying…it’s sink or swim time!  We have given you all of the tools you need to swim, (life raft, 
safety vest, paddle board, etc) or at the very least, stay afloat and not drown!  Now we are going to throw you out into
the middle of the ocean, and it’s up to you to use your tools we’ve given you to not only survive, but to make it safely 
back to shore!  My get_character_details method was likened to what I perceived as a shark coming towards me at 
rapid speed with it's mouth opened and all of it's teeth showing, only to find out that it was just a dolphin the entire 
time!  Ha Ha!  I am so glad I have completed this project, and I am looking forward to my Sinatra project next!



# Things I can do better: 


* I created and published my breaking_bad_project_cli to Rubygems.  However, after publishing, I realized I did not 
update the summary.  Therefore, I have to go back and update this while ensuring the correct version is noted as well. 

* Practice speaking my code a lot more.  I am fine writing it, but I need to be just as comfortable communicating my 
code.  So I will be practicing communicating my code a lot more!

