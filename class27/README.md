# Reading Notes

# Class 27 - Props and State

## 1. Does a deployed React application require a server?

A deployed react application does not require a server because it gets compiled into static html and js files.

## 2. Why do we prefer to test a React application at the behavior rather than the unit level?
We test the behavior of the app instead of unit testing because React is a view library which means the UI will constantly change. It would take an extremely large time to write unit tests for every UI change we make, so we instead only focus on the behavior

## 3. What does npm run build do?

Converts a React application into static html, css, and js files

## 4. Describe the actual composition / architecture of a React application
Index.js - The root of the application which renders our app into a static html page that has an ID of root
App.js - The parent component that renders all child components. Can also contain global state if designed in that manner
Child components - Smaller js files that usually perform one or two actions which then can be rendered into the parent component

## Document the following Vocabulary Terms

- **BDD** - Behaviour Driven Development (BDD) is a synthesis and refinement of practices stemming from Test Driven Development (TDD) and Acceptance Test Driven Development (ATDD).[Resource](https://www.agilealliance.org/glossary/bdd/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'bdd))~searchTerm~'~sort~false~sortDirection~'asc~page~1))

- **Acceptance Tests** - An acceptance test is a formal description of the behavior of a software product, generally expressed as an example or a usage scenario.  [Resource](https://www.agilealliance.org/glossary/acceptance/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'acceptance*20test))~searchTerm~'~sort~false~sortDirection~'asc~page~1))

- **mounting** - Mounting is the process of outputting the virtual representation of a component into the final UI representation (e.g. DOM or Native Components). [Resource](https://stackoverflow.com/questions/31556450/what-is-mounting-in-react-js#:~:text=Mounting%20is%20the%20process%20of,element)%20in%20the%20DOM%20tree.)

- **build** - npm run build creates a build directory with a production build of your app. [Resource](https://create-react-app.dev/docs/deployment/)

## Preview 

1. Which 3 things had you heard about previously and now have better clarity on? State, lifecycle, props

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? Lifecycle methods, hooks, dynamic forms

3. What are you most excited about trying to implement or see how it works? Implementing dynamic forms

