# Sidebar Practice with Context API

This is a simple app that includes a sidebar and a modal. Both the sidebar and modal can be toggled by clicking buttons on the home component. The toggling functionality is achieved by changing the global state, which is made available through a context component. The classes for the sidebar and modal are set dynamically using ternary operators.

# How It's Made

The app is built using ReactJS and utilizes the Context API for managing global state. The sidebar and modal components are rendered conditionally based on the global state value. The classes for displaying or hiding these components are set dynamically using ternary operators, depending on whether the state is toggled or not.
Tech used

ReactJS
Context API

# Functionality

The app provides the following functionality:

Sidebar Toggling: Clicking the toggle button on the home component will toggle the visibility of the sidebar.
Modal Toggling: Clicking the toggle button on the home component will toggle the visibility of the modal.
Global State Management: The toggling functionality is achieved by changing the global state, which is available through a context component. The components use this global state to determine their visibility.

# What I Have Learned

During the development of this app, I have gained knowledge and experience in the following areas:

ReactJS: I have furthered my understanding of ReactJS and its component-based architecture.
Context API: I have utilized the Context API to manage global state and provide data and functionality across different components without prop drilling.
Dynamic Class Assignment: I have learned how to set classes dynamically using ternary operators, allowing for conditional rendering and styling of components.
