# Interview Answers

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

   Context API helps solve the problem of excessive prop drilling within React. It helps to keep state clean.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

   Actions provide the payload of information that will be plugged into the reducer.
   Reducers receive the payload from an action and use it to change state in one form or another.
   The store is a state container that can be universally accessed throughout the app as needed.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

   It makes the reducer flow asynchronous and changes our action-creators to allow them to make API calls.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

   I preferred using redux. It felt very intuitive to me and the code needed was concise and easy to follow.
