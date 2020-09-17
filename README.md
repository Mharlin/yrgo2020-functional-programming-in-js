## Presentation about functional programming in js for Yrgo in Gbg
The presentation can be seen on mharlin.github.io/yrgo2020-functional-programming-in-javascript

Exercises can be found at https://www.codingame.com/playgrounds/2980/practical-introduction-to-functional-programming-with-js/pure-functions

# Modify and build the presentation
The source for the presentation is in index.adoc and to build the output file run `npx asciidoctor-revealjs index.adoc`
The presentation is using asciidoctor, asciidoctor-revealjs and asciidoctor-revealjs-klipse (live code)
To serve the content light-server can be used: `light-server -w index.html -s .`
For continous build run: `ls *.adoc | entr npx asciidoctor-revealjs index.adoc`
