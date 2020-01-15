# Site-Connectivity-Checker
The Site Connectivity Checker visits a URL and returns the status of the URL: it is either live or not.
We shall be using the Pandas Library for exatracting website data from a csv file


When you visit a URL, you expect to get the requested pages on your browser. But this is not always the case. Sometimes, sites can be down, so you won’t get the desired results. Instead, you’ll be presented with error messages. You can keep trying a site that is down, till it comes up and you get the information you need.

This is where the Site Connectivity Checker project comes in. The Site Connectivity Checker visits a URL and returns the status of the URL: it is either live or not. The Site Connectivity Checker will visit the URL at intervals, returning the results of each visit.

Instead of manually visiting a URL, a Site Connectivity Checker can do all of that manual work for you. This way, you’ll only get the results of the check without having to spend time on the browser, waiting for the site to go live.

# Server responses to take note of 

    Informational responses (100–199),
    Successful responses (200–299),
    Redirects (300–399),
    Client errors (400–499),
    and Server errors (500–599).
