# tfl
an incomplete and yucky TfL API wrapper, for python

This is a very... thin wrapper.

It consists of a single object ```TfL``` (that can optionally be instantiated with the API ID and key) which has methods that query the API calls in https://api.tfl.gov.uk/. These methods return the result of the call, as a parsed JSON object (i.e. a Python dict/list data structure). It doesn't do anything clever with the results - that is left up to you.

It currently only works with BikePoint related calls (the first section on https://api.tfl.gov.uk).
