# Intro to Testing

## Scenario

Here at GOV.UK we have a bunch of **very** clever folks who have developed the ability for our users to create an account. Accounts cover all GOV.UK sites and services. An account lets our users log in, complete a number of tasks, update their account details and personal preferences, and of course log out.

Recently though, user research has identified a key piece of missing functionality...

Our users would like the ability to save tasks for later completion. They want to know what is pending, what is in progress and what is done. Tasks can have a 'due by' date - this will be used when the user logs in to remind them that they have upcoming or in progress tasks together with the date on which the task should be completed by.

Tasks are created by the user by clicking a 'Create task' button on an appropriate GOV.UK page. This creates an entry in the task list containing the users unique ID and the URL of the page - so that the user can simply click each task on their todo list and complete or carry on working on it. Before creation the user has the option to add notes and set the 'due by' date - if they want.

Once created an entry can be completed or deleted. The user can update the notes, 'due by' date, and the status on each entry. Deleted tasks cannot be recovered. Completed tasks remain on the list until the user deletes them.

As the backend developer on the project, you have been asked to create the backend solution. You don't need to worry about the user account functionality, the buttons on the UI, how/where the data is stored or how the data gets from the webpage to the server. Just give the team the core task list functionality plus the ability to list all tasks or only the outstanding (in progress, pending) tasks for a specific user.

> I've [made a start](task-list.rb) 😺
>
> My adivce is trust the TDD cycle (red-green-refactor) and let the tests drive your design. You've got this 👍
>
>
> *... your tech lead*

## References

- [MiniTest](https://github.com/minitest/minitest)
- [MiniTest Assertions API](https://ruby-doc.org/stdlib-2.0.0/libdoc/minitest/rdoc/MiniTest/Assertions.html)
