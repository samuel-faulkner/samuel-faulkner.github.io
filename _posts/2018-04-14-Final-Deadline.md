## What did I do this past week?
This past week was less busy than most. For the IDB project, my team and I mostly worked on the issues given to us by our "customers". We got nearly all of them done as they were mostly minor fixes and features. I'd like to think its a testament to how well we've structured our project and the quality of our project. I also looked into [D3](https://d3js.org/) and have been playing around with it in order to implement it in our own IDB project as well as the page we're making for the team of whom we're customers.

## What's in my way?
[React-D3](http://www.reactd3.org/) is a waste of time. It's out of date and I spent a lot of time trying to get it to work to no avail. Specifically, it relies on [prop-types](https://www.npmjs.com/package/prop-types) being within the [React](https://reactjs.org/) library itself, which hasn't been the case since version 15.5. It's also not necessary at all. [React-Bootstrap](https://react-bootstrap.github.io/) is a necessary React library in order to use [Bootstrap](https://getbootstrap.com/) whilst using React instead of [jQuery](https://jquery.com/), whereas React-D3 only barely wraps D3 method calls with React's lifecycle methods. The only problem I have using D3 itself is that it has so many examples it's confusing to find relevant help.

## What will I do next week?
Next week I plan on finishing up the stuff I'm working on for the last phase of IDB. I'll then start work on the presentation and the extra page we're making for [majorpotential.me](http://majorpotential.me/). These items aren't due until my team and I present, so we'll definitely be focused on our own project before tackling these last requirements.

## What's my experience with the class?
The refactoring portion of the class has been tedious at best, and very boring at worst. It seems like the book we've been assigned to read is very out of date and the examples we've been to work on in class have been super easy and fast to implement despite receiving a lot of time within lecture to work on them. There is a bright side though-- hopefully, we get these kinds of refactoring questions on the next test.

## What's my pick-of-the-week?
[React-Measure](https://github.com/souporserious/react-measure) is an excellent supplement to implementing D3 in React. D3 requires [SVG](https://developer.mozilla.org/en-US/docs/Web/SVG) HTML elements with pixel dimensions, which is very hard to anticipate in a dynamic way. React-Measure solves this problem, collecting the dimensions of its child element and thus providing the dimensions to the SVG element that D3 is rendered in.