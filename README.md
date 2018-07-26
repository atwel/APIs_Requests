# APIs_Requests
Tutorial introducing APIs and web requests

This repository contains teaching materials for introducing people with basic knowledge of Python to Application Programming Interfaces and doing web requests.

The notebook introducing APIs focuses on the Twitter API as exposed by the `python-twitter` package. However, users don't use that package directly and instead use a custom package
that streamlines the processing and presentation of the data. I chose this route because it will give users a chance to interact with an API and understand more about the workflow 
but also get to do some of the fun stuff that makes it worth coming back. 

The notebook introducing web requests scrapes a website for all of Bob Dylan's lyrics using the `requests` package. It uses `beautiful soup` to parse the HTML. It then does some light data cleaning
and even allows users to analyze the text via the (smallest) GloVe word embedding.
