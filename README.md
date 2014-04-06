Template.pd
========

Template.pd is a template for generating algorithmic music for live settings or for recording.

I use PD to make entire songs. This project is intended to be a framework that will allow for more rapid patching of full tracks.

The structure is as follows:

First a centralized pulse is generated and counted. This count is sent under the name "countoff."

A number of N voices receives this count and generates note data with it

Requires PD-Vanilla .45
