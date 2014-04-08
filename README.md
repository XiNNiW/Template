Template.pd
========

Template.pd is a template for generating algorithmic music for live settings or for recording.

I use PD to make entire songs. This project is intended to be a framework that will allow for more rapid patching of full tracks through convention over configuration. 

The structure is as follows:

There are a number of modules which when connected in a chain form a structured sound (like a beat or a melody). 

First note data is generated by event generators. That data is then sonified by signal generators or synthesizers. That audio is then manipulated by effects, and then mixed and panned before being send to the main bus for audition. 

In other words, each musical voice is made of a stack of event\_gn's, sig\_gn's, effectrs, and mixrs. Each of these modules must be entirely plugable, they must be able to be dynamically loaded and saved, and they must follow a set of guidelines. For example, event_gn's will all have the same number of inlets and outlets.

The project isn't very far along yet, so there may not me much to see here..... yet. I've made some music with much messier versions of this idea though if you want a listen: [a link](https://soundcloud.com/xinniw)

Requires PD-Vanilla .45
