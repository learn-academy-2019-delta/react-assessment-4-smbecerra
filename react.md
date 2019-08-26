# ASSESSMENT 4: REACT ASSESSMENT
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.  

1a. Indicate which of the following statements about React are false:

- React is a modern, efficient answer to complex UI applications
- React will only render on the server using Node.js <----- FALSE 
- React is a full stack framework for modern web applications <---- FALSE
- React is a flexible library that plays the role of V in an MVC framework
- You should always update a component's state directly using this.state
- React is made up of encapsulated components that manage their own state
- React components render HTML

1b. Add an interesting true fact about React to the list.

2. What are "smart" and "dumb" components? Explain the difference and also add why we bother to make the distinction between them.

  Your answer: smart components create and maintain state and properties for the app, dumb components inherit from these smart components.

  Researched answer: Dumb components simply present a current state, Smart components create and maintain these states for an app. 
  The smart component does all of the heavy lifting of passing on data toward the dumb component. 



3. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?

  Your answer: adds to our dependencies. package.json

  Researched answer: "yarn add" addes packages to our dependencies. When a new package is added, package.json is automatically updated as well. 



4. How would you explain state to a friend who doesn't know code?

  Your answer: State is date/information maintaned in a private place, such as a safe.

  Researched answer: State is data maintaned inside a component. It is only maintained within that component. e.g. A book placed in a bookcase stays there until is removed. 



5. What is the difference between component state and props? Your answer should include a short explanation of both.

  Your answer: State is data maintaned inside a component. Props is data passed in from a parent component. 

  Researched answer: Props is data passed in from a parent component. They are read-only in the child component which receives them. State is owned and updated in the local component.
