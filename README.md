# melee-elo
This project aims to make a interactive visualization of the ELO ranking information created by /u/rahsosprout:
https://www.reddit.com/r/smashbros/comments/76cpy8/ranking_the_top_melee_players_using_elo/

Credit to https://bl.ocks.org/mbostock/3884955 for most of this code.

### Getting Started:
In the directory of the project, start a basic server with your tool of choice.  
	
	# example with ruby
	$ ruby -run -e httpd . -p 8000   
	
	# example with python
	$ python -m SimpleHTTPServer 8000 
	
Then open `localhost:8000/index.html ` in your browser.

### TODO:
- host on heroku 
- make zoom only work for chart, make axis scale
- make filtration by score?
- cross reference ssbmrank?
- warning if user wants to load too many players
- lines get thinner on zoom
- optimize performance
- hover to see player name, liquipedia(?)
- filter by improvement rate, jumps, rank
- get rid of line ups from zero (new challenger approaches?)
- cross reference tournament dates
- individual player search

