For anyone who thinks my passwords for gmail are still working. Guess again.


Anyways. I'd like to present my flexget config in all of it's glory. A big thanks to atlanta800

There are some private portions of my config and if you'd like help with those, 
I can provide assistance on a case-by-case basis

Basically, what we do here is take an rss torrent feed, pipe it through this config and Flexget
pull out all of the shows that I specify in series.yml, find the best qualities, then shoot them over to deluge.

for some reason XBMC has decided not to include rar support in their Linux mainline. So we must unrar, 
but who's got time for that shit... So for rar's we pipe them to a new place and when they finish downloading
deluge spits off this execute script that unrar's them, places that output file in another place, and then runs 
a special flexget config over them! pretty freakin' sweet.

