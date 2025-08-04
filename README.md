# To Do List App using Angular and Docker

## How to Run

<br>

With Docker installed, run the Docker image, as it is shown below.

```
docker run -p 4201:4200 angular-docker
```

<br>

later, open the URL `http://localhost:4201/` in your browser.

<br>

## Brief Explanation

<br>

This repository was made to study how to create Docker images and run containers using a simple Angular project.

The project is a list of items, where new items can be added, removed and edited. Besides that, a simple filter was implemented that shows specific portions of the data based on state (marked, unmarked and all items).

Besides the Docker implementation, this project helped me to understand basic Angular concepts, such as Components, Interface, interpolation, input and output decorators, @for and @if statements in template file, get, add and remove functions in typescript.
