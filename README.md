# Data Observability

I want to be able to connect to a database, view a table and see the data over time segmented by as many columns as I want.

## Task 1: Get a client up and running
I need to be able to deploy and productionize my code. I'm going to build a client that can connect to a backend and verify it is successful just by giving me a "Hello World"

### Technology Base:
I'm not working on a team or in a project. This is for my personal use and learning. We are going to be doing data visualization, so I want to pick a language that has strong visualization tooling. Python immediately comes to mind because I work with it a lot, and I know it has good data visualization tooling, and it's flexible enough to run a web application client too. This is mainly a learning project, so the language I pick is primarily influenced by what I want to learn. I am _always_ interested in learning _all the things_, so I'm not gonna lie, I briefly looked at doing it in rust or go. It's totally possible, but in the end, my primary learning goals for this project are:

- Work with polars
- Build a docker container that I can pull in to almost any environment
- See what I can do for observability of data pipelines.

In this case, it might be a good idea to constrain myself to _these things_, just so that I don't lose motivation because I'm struggling with too much new. I could build the frontend with react and typescript, but I want to keep this project small and streamlined. I want to actually be able to use it at some point. Also, I have never built a frontend in python, so I won't be bored :-)

