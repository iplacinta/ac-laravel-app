# Amherst College
### Reporting and Applications Developer Project
Thank you for your interest in the Reporting and Applications Developer position. 

For the next part of the interview process, you will need to fork this repository and then complete the tasks below.

Once finished with your work, invite GitHub user iplacinta to review your PR and leave comments.

Show us what you can do. Be creative, but deliver the requirements.

### Deadline: One week from when you are given this project.

## Tasks
1.	Fork this repository, and create a new branch for your work.
2.	Modify users table, add Boolean column ‘is_admin’ with a default of false, and string column ‘bio’
3.	Create seeders that will generate the following users:
      -	One admin user, with the name “Amherst Admin”,
      -	Name: Amherst Admin
      -	Email: admin@mail.com
      -	Two other admin users
      -	Five non-admin users
      -	All seeded users (including admins) should have the password ‘testpass’
4.	Create a function “specialName” that returns ‘AC ‘ prefixed to the user’s name, append it to the user so that it’s always available.
5.	Create a resourceful controller UserController and a resourceful route(s) for that controller.
      -	Cleanup unused items
      -	Add ‘auth’, ‘verified’ middleware.
6.	Modify dashboard to show you a list of users.
      -	Display each user in a card style (make a reusable component)
      -	The card should include the following
      -	An image (use https://avatar-placeholder.iran.liara.run/avatars to get an image for each user, you don’t need to store these images, but each use should have it’s own image (unique) and it should remain the same on each page load)
      -	User’s “Special Name” (see #4)
      -	Something to indicate whether the user is a regular user, or admin.
      - User’s bio.
      - Edit button (takes you to users edit screen).
      -	Delete button that deletes the user.
      - Make the cards look good.
7.	Add ‘Create User’ button to top of dashboard (takes to create user screen)
8.	User Create Screen
      -	Name input
      -	Email input
      -	Password input
      -	Bio textarea
      -	Is Admin checkbox
      -	Cancel button
      -	Submit button
9.	User Edit Screen
      -	Image (not editable)
      -	Name input
      -	Email input
      -	Bio textarea
      -	Is Admin checkbox
      -	Cancel button
      -	Submit button
10.	Authorization
       a.	All users can view the dashboard, but only admins can make changes / create / delete users.
       b.	Regular users can edit themselves, but cannot make themselves admins, or delete.
11.	Create appropriate server side validation for create / update / users
12.	Write 5 good tests

## Pull Request
When finished, create a pull request into the main branch and invite use to review your code. Notify us back via Email to start the review process.
