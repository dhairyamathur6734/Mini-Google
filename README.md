# MiniGoogle 1998 🔍

An interactive, single-file demo that compares two ways of ranking web pages:

- **Old way:** counts how many times the search word appears.
- **PageRank way:** ranks pages by how often a random surfer lands on them (100,000 simulated moves, damping factor 0.85).

Search "pizza" and the keyword-stuffed spam page wins the old ranking but sinks to the bottom with PageRank. Click **"Add 3 fake pages"** to watch link-farm spam get exposed: spammers can stuff keywords, but they can't force real sites to link to them.

## Run it
Download `index.html` and open it in any browser. No install, no dependencies.

## Built with
Plain HTML, CSS and vanilla JavaScript.
