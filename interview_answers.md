# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

    A. The issues of components deep into a tree needing data from above, causing a deep prop drill. API context makes a series of values available to anything engulfed in the provider.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

    A.  * actions : are a way to group logic together that will be used for a certain outcome, like showing up a name in a display by fetching the users name, fetching in this case being an action
        * reducers: are the where the state which teh action wil lbe changing or telling it to how to change it. with fetching the user name, the reducer understands the action and does the state   management, like changing the name state
        * store: is what allows the entire application to have acceess to the Actions/Reducers as well as easing prop drilling

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

    A. thunk can call actions in sequence while actions can only once at a time. it saves time in code


4. What is your favorite state management system you've learned and this sprint? Please explain why!

    A.  reducers are definetly my go to but they seem a bit too much for simple thingss
