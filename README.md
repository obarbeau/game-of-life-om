# An Om/React client of the game of life

Based on Christophe Grand's [solution](https://github.com/clojurebook/ClojureProgramming/tree/master/ch03-game-of-life) in the book Clojure Programming

The visualisation is inspired by the excellent presentation of React.js by [steveluscher at react-supervanjs-2013](https://github.com/steveluscher/react-supervanjs-2013)

The purpose is to help people discover and understand Om/React during a dojo at the Paris Clojure Meetup.


## Getting starter

Based on David Nolen's template : mies-om

`lein cljsbuild auto`


Open the project with LightTable

You are presented en empty world, free of any cell.

### Possible actions are


* Create new cells by the mouse actions : `click, hover, click`

* Create non contiguous cells by pressing `esc` key before the second `click`.

* Choose predefined cells configuration from the drop down list.

* kill all cells by clicking on "Wipe board" button or hitting `space` bar.

* Vary the next generation speed by using the slider

* Click on the "Mark" button to color each location with direct DOM manipulation.


## Resources

Watch this instructive and fun presentation of [React.js by steveluscher at react-supervanjs-2013](http://www.youtube.com/watch?v=1OeXsL5mr4g)


I warmly recommand you to study this article, it contribute greatly to understand the organisation of a React.js app
and helps you to build your own app :
[Thinking in React By Pete Hunt](http://facebook.github.io/react/blog/2013/11/05/thinking-in-react.html)


There is a nice introduction of Om in theses [slides by Sean Grove](http://sgrove.github.io/omchaya/docs/presentation.html#/)
