---
####################
### INSTRUCTIONS ###
####################
# This file is a template to create new events.
# _Don't_ remove any text before the colons at the beginning of each line,
# only edit what is after the colon. Example:
# Don't remove the word nor colon on 'description:'
#
# Every line starting with a hash symbol (#) is a comment. It will be ignored
# and can be safely removed, including these instructions.
###############


###########
### SEO ###
###########
# The title of the page, displayed by the browser on the title of the window.
# Ideally this is the same as the name of the event.
title: Mayato Party

# Description for this event. This will be rendered as a <meta> tag in the HTML,
# and displayed on the /events page. Keep it short.
# Linebreaks are ignored, but they _must_ start with two spaces.
description: We invite the Prague blockchain developers community to join us for an evening of networking, drinks and meeting the Algorand team.

#####################
### EVENT DETAILS ###
#####################
# The name of the event you're creating.
# Ideally this is the same as the title.
name: Mayato Party 

# There _needs_ to be one hyphen before each paragraph.
# Linebreaks are ignored, but they _must_ start with two spaces.
# Indentation is crucial:
# Two spaces before the hyphen, four spaces before the text. _No_ tabs allowed.
# Add or remove paragraphs as needed, but remember the hyphen before each entry.
synopsis:
  -
    We invite the Prague blockchain developers community to join us for an evening of networking, drinks and meeting the Algorand team to hear about the revolutionary alternative blockchain, developed from the first principles and enabling continuous progress.
  -
    Turing Award winner and an MIT professor Silvio Micali will tell you about how Algorand is changing the conversation in the blockchain space.
  -  
    'Agenda:' 
  -   
    list:
        - '18:30 - 19:30 Walk-in & Networking'
        - '19:30 - 20:15 Algorand Project Presentation + Q&A by Silvio Micali'
        - '20:15 - 20:45 Algorand Developer Tools by Naveed Ihsanullah'
        - '20:45 - 21:00 Algorand Ecosystem, Community and Partnerships by Şahver Kaya'
        - '20:30 - 22:00 Networking'
        - '22:00 - 01:00 Drinks at Avion 58 bar (4min walk from Paralelní Polis)'
  -
    'Transportation options from Devcon4 venue to Paralelní Polis: [Google Maps](https://www.google.com/maps/dir/Prague+Congress+Centre,+5.+kv%C4%9Btna+1640%2F65,+140+21+Praha+4,+Czechia/Paraleln%C3%AD+Polis,+D%C4%9Blnick%C3%A1+475%2F43,+170+00+Praha+7,+Czechia/@50.0818121,14.4163387,14z/data=!4m14!4m13!1m5!1m1!1s0x470b9464c186eb79:0x4d26855708eb61f7!2m2!1d14.428506!2d50.062033!1m5!1m1!1s0x470b94b186427997:0xcad994427e27c9c0!2m2!1d14.4505577!2d50.1033854!3e0)'
  -
    'Event partner: [Lemniscap](https://lemniscap.com)'

# The date should be in the format year-month-day (ISO 8601).
# Example: 2018-02-28
date: 2019-10-05
# The date when the event ends. Can be left empty or set to the same day the
# event starts.
endDate: 2019-10-05

# Set the time in 24 hours format, surrounded by quotes.
# _Only_ the starting time!
# Example: '18:30'
time: '18:30'
# Time when the event ends. Can be left empty.
endTime: '01:00'

# The URL where to akquire the tickets. Can be left empty.
tickets: https://www.eventbrite.com/e/algorand-blockchain-meetup-prague-tickets-50969326628

# If the entrance is free, set zero (0) as the price, or leave it empty.
# _Don't_ write the currency symbol (EUR symbol will be used).
price: 0

# The name of the venue where the event will be held. Can be left empty.
venue: Paralelní Polis

# The address to link to a Google map. Please test the address on Google Maps.
# Example: 5. května 1640/65, 140 21 Praha 4
address: Delnicka 43, 170 00 Praha 7, Czechia

# The category of the event. Valid options:
# - conference
# - event
# - hackathon
# - workshop
# - party
# Use _only_ one, and don't capitalize.
category: event


#################
### SPEAKERS ####
#################
# There _needs_ to be one hyphen before each entry.
# Linebreaks are ignored, but they _must_ start with two spaces.
# Indentation is crucial:
# Two spaces before the hyphen, four spaces before the text. _No_ tabs allowed.
# Add or remove speakers as needed, but remember the hyphen before each entry.
speakers:
  -
    # Required.
    name: Silvio Micali

    # Can be left empty.
    title: Founder

    # Can be left empty.
    company: Algorand

    # Just the twitter handle, without Twitter's URL, nor the '@' symbol.
    # Can be left empty.
    twitter: Algorand

    # The full URL, including http(s)://. Can be left empty.
    companyURL: https://algorand.com

    # The bio is a single line.
    # Linebreaks are ignored, but they _must_ start with two spaces.
    bio: Silvio Micali is the Founder of Algorand, a revolutionary new blockchain that solves the "Blockchain Trilemma" by being truly scalable, secure and decentralized. 
  -
      name: Naveed Ihsanullah
      title: Head of Engineering
      bio: Naveed Ihsanullah is a senior engineering leader and technologist fascinated by distributed systems and performance. 
      companyURL: https://algorand.com
      company: Algorand
      twitter: naveedi
  -
    name: Şahver Kaya
    title: Head of EMEA
    company: Algorand
    companyURL: https://algorand.com
    twitter: sbinici_
    bio: Şahver Kaya is an international executive with extensive experience in USA, Europe and Asia.
  
### DON'T MAKE CHANGES BELOW THIS LINE! ###
---
<!-- ### DON'T MAKE CHANGES BELOW THIS LINE! ### -->

<Event-Content/>
