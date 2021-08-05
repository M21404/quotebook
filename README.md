# quotebook

Quotebook for M21404

## Overview

Contributions welcome. Keywords are 'Transcendental, Irreverence, sensuality, mono no aware, topless males'

## To-do

- [x] Implement quote scraping in Shirator
- [x] Finish theme css loading framework to make it easier to create themes
- [ ] Add Quil/Processing animations
- [ ] Blissful sound bites

## Theme Ideas

- [ ] 'Smithsonian Backswatter'
- [ ] Botanical Rose
- [ ] Ugly cute Frog 'tying a cherry stem'.
To get an interactive development environment run:

## Possible inspirations

https://www.youtube.com/watch?v=V7PTQ-vLP_w

http://stoney.sb.org/eno/oblique.html

## Setup

To get an interactive development environment run:


    lein figwheel

and open your browser at [localhost:3449](http://localhost:3449/).
This will auto compile and send all changes to the browser without the
need to reload. After the compilation process is complete, you will
get a Browser Connected REPL. An easy way to try it is:

    (js/alert "Am I connected?")

and you should see an alert in the browser window.

To clean all compiled files:

    lein clean

To create a production build run:

    lein do clean, cljsbuild once min

And open your browser in `resources/public/index.html`. You will not
get live reloading, nor a REPL. 

## License

Copyright © 2014 FIXME

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.
