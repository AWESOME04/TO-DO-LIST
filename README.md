# Frontend Mentor - Todo App Solution

This is a solution to the [Todo app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/todo-app-Su1_KokOW). Frontend Mentor challenges are a great way to improve your coding skills by building realistic projects.

## Overview

### The Challenge

The challenge was to create a responsive and interactive todo app with various features. Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Add new todos to the list
- Mark todos as complete
- Delete todos from the list
- Filter by all/active/complete todos
- Clear all completed todos
- Toggle light and dark mode
- **Bonus**: Implement drag and drop to reorder items on the list

### Screenshot

![lighth_mode](https://github.com/AWESOME04/TO-DO-LIST/assets/102630199/ca069b2a-8f20-470e-abbb-a864d8a8bf73)


![dark_mode](https://github.com/AWESOME04/TO-DO-LIST/assets/102630199/473d690f-7af9-40d8-872b-d5567b2c56ae)

### Links

![Live Site URL](https://awesome04.github.io/TO-DO-LIST/)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- React - JavaScript library
- Next.js - React framework
- Styled Components - For styles

### What I Learned

During this project, I learned how to effectively structure a React application and manage state using React hooks. Implementing the drag and drop functionality for reordering items was a challenging task that taught me about handling complex user interactions in a web application.

Here's an example of code I'm proud of:

```javascript
// This function handles the drag and drop functionality for reordering items
const handleDragEnd = (result) => {
  if (!result.destination) return;

  const updatedTodos = Array.from(todos);
  const [reorderedTodo] = updatedTodos.splice(result.source.index, 1);
  updatedTodos.splice(result.destination.index, 0, reorderedTodo);

  setTodos(updatedTodos);
};
```

### Continued Development

In future projects, I want to focus on further improving my knowledge of React and exploring more advanced state management techniques like Redux. Additionally, I plan to enhance my understanding of accessibility best practices to create more inclusive web applications.

### Useful Resources

- [MDN Web Docs](https://developer.mozilla.org/): A comprehensive resource for HTML, CSS, and JavaScript documentation.
- [Styled Components Documentation](https://styled-components.com/docs): The official documentation for Styled Components, which helped me style my components in a more maintainable way.

## Author

- Software Engineer, Intern - [AWESOME04](https://github.com/AWESOME04)

- LinkedIn - [Evans Acheampong](https://www.linkedin.com/in/evans-acheampong-982315232/)
- 
## Acknowledgments

I want to thank the Frontend Mentor community for providing this challenge and giving me an opportunity to practice and improve my front-end skills. I also received valuable feedback and support from fellow developers in the community, which was instrumental in completing this project.

