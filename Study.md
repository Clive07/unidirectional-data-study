[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# Unidirectional Data Flow: Study

Use [DuckDuckGo](https://duckduckgo.com/) or your preferred search engine along with the provided resources to research and answer the [questions below](#questions).

## Required Reading

- [What is unidirectional data flow in React](https://flaviocopes.com/react-unidirectional-data-flow/)
- [Lifting state up](https://reactjs.org/docs/lifting-state-up.html)
- [Inverse data flow](https://dev.to/isabelxklee/understanding-inverse-data-flow-in-react-3cg7)
- [Container vs Representational Components](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0)
- [Conditional rendering](https://reactjs.org/docs/conditional-rendering.html)

## Questions

1. Describe what is unidirectional data flow.

   ```
   The idea is that data has only one way to go from one section of the app to another. With React this is done in a 3 point cycle. State which sets up View. View granting ability to make Actions. Actions can force a updating of the State. updated State now sets up the View.
   ```

2. What does it mean to have a single source of truth for data?

   ```
   essentially it means a parent component is passing both data down and update state functions to one or multiple child components so they can act upon data changes and update the state
   ```

3. What is the limitation of inverse data flow?

   ```
   Data is only capable of passing down and up components with a direct relationship e.g. parent to child and child to granchild. Siblings are not able to receive this data flow.
   ```

4. Why is it a good practice to separate container and representational components?
   ```
   It is always useful to have a separation of concerns. You are in a manner of speaking dividing up the code for the UI and the code to make things work.
   ```

### Response Guidelines

Please follow these guidelines as you answers these questions:

- Cite any relevant sources consulted during your research
- Do not reply using direct quotes from the source material
- Provide an answer using your own words and voice
