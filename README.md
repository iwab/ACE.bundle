## Plex plug-in that plays live streams using acestream engine ##

### Introduction ###
A [Plex Media Server](https://www.plex.tv/downloads) plug-in that scrapes reddit's pages looking for acestream links and then populate a list understandable by plex.

### Supported subreddits ###
* boxingstreams
* nbastreams
* nflstreams
* MMAStreams
* motorsportsstreams
* soccerstreams_other

### Requirements ###
In order to stream content you need acestream engine on the same host listening on port 6878, I personally start the engine with options "--log-stdout --client-console"

### License ###
Original Copyright © 2018-2018 Syco
Kudos to [Syco](https://github.com/syco) for developing this, merely updating to include my choice of reddit subs.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU General Public License](http://www.gnu.org/copyleft/gpl.html) for more details.
