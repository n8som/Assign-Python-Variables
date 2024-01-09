# Assign-Python-Variables

<h2>Introduction</h2>

Variables help security analysts keep track of a variety of security-related information. For example, analysts may need to create Python variables for the users who are allowed to log in, the number of login attempts that they're permitted, and the current number of attempts that a user has made.

In this lab, I'll practice assigning values to variables and determining their data types.

<h2>Scenario</h2>

I am a security analyst who is responsible for writing code that will automate analysis of login attempts made to a specific device. As the first step, I'll need to create variables to keep track of information relevant to the login process. This information includes the device ID, list of approved usernames, maximum login attempts allowed per user, current login attempts made by a user, and login status.

Throughout this lab, I'll assign these variables and check the data types of the variables.

<h2>Task 1</h2>

In my work as an analyst, imagine there is a device only users specified on an allow list can access, and its device ID is "72e08x0".

In the following code cell, assign this value to a variable named device_id. Then, display the contents of the variable and observe the output.
​
![image](https://github.com/n8som/Assign-Python-Variables/assets/110139109/c5bff8c2-c8f1-47c5-953c-9f00aa8f715c)

<h2>Task 2</h2>

Now that the variable device_id is defined, I can return its data type.

In this task, use a Python function to find the data type of the variable device_id. Store the data type in another variable called device_id_type. Then, display device_id_type to examine the output.

![image](https://github.com/n8som/Assign-Python-Variables/assets/110139109/3f2aa2d6-73cc-4011-98f6-9c6e63b17635)

72e08x0 gets outputted when you display 'device_id_type'

<h2>Task 3</h2>

As I continue my work, I'm provided a list of usernames of users who are allowed to access the device. The usernames with this access are "madebowa", "jnguyen", "tbecker", "nhersh", and "redwards".

In this task, create a variable called username_list. Assign a list with the approved usernames to this variable. Then, display the value of the username_list variable.

![image](https://github.com/n8som/Assign-Python-Variables/assets/110139109/4dab1632-a56f-43b0-88a0-239ecab9b848)

<h2>Task 4</h2>

In this task, find the data type of the username_list. Store the type in a variable called username_list_type. Then, display username_list_type to examine the output.

![image](https://github.com/n8som/Assign-Python-Variables/assets/110139109/532867ce-8f74-4dd4-9a16-f4165a138a0a)

<h2>Task 5</h2>

Now, imagine that I've been informed that the previous list is not up-to-date and that there is another employee that now has access to the device. I'm given the updated list of usernames with access, including the new employee, as follows: "madebowa", "jnguyen", "tbecker", "nhersh", "redwards", and "lpope".

In this task, reassign the variable username_list to the new list. Run the code to display the list before and after it's been updated to observe the difference.

![image](https://github.com/n8som/Assign-Python-Variables/assets/110139109/63696161-51fb-4759-964b-416664728fd6)

I can see that Python outputs the first list and then the updated list afterward because of how the commands were ordered.

<h2>Task 6</h2>

In this task, define a variable called max_logins that represents the maximum number of login attempts allowed per user. Store the value 3 in this variable. Then, store its data type in another variable called max_logins_type. Display max_logins_type to examine the output.​

![image](https://github.com/n8som/Assign-Python-Variables/assets/110139109/8f03734a-d44e-41bd-888a-de206d0ad769)

The output above shows that the data type of max_logins is int, which means that max_logins stores an integer value.

<h2>Task 7</h2>

In this task, define a variable called login_attempts that represents the current number of login attempts made by a user. Store the value 2 in this variable. Then, store its data type in a variable called login_attempts_type. Display login_attempts_type to observe the output.

![image](https://github.com/n8som/Assign-Python-Variables/assets/110139109/34741e51-1135-43b4-a72a-74449595b447)

The output above shows that the data type of login_attempts is int, which means that login_attempts stores an integer value.

<h2>Task 8</h2>

In this task, I'll determine the Boolean value that represents whether the current number of login attempts a user has made is less than or equal to the maximum number of login attempts allowed.

![image](https://github.com/n8som/Assign-Python-Variables/assets/110139109/4a7e2dc8-b5cc-4a7a-addb-d3e35c42981d)

The output above is True, which indicates that login_attempts is less than or equal to max_logins. In other words, the current number of attempts the user has made to log in has not yet exceeded the maximum number of attempts allowed.

<h2>Task 9</h2>

This code continues to check for the Boolean value of whether max_logins is less than or equal to login_attempts. In this task, reassign other values to login_attempts. For example, I might choose a value that is higher than the maximum number of attempts allowed. Observe how the output changes.

![image](https://github.com/n8som/Assign-Python-Variables/assets/110139109/269edcfe-efaa-4392-9645-a1524a63b34a)

The Boolean value in the output changes depending on the value assigned to login_attempts. For example, when login_attempts is assigned to 5, the output is False, which indicates that login_attempts is not less than or equal to max_logins. In other words, the current number of login attempts the user has made has exceeded the maximum number of attempts allowed.

<h2>Task 10</h2>

Finally, I can also assign a Boolean value of True or False to a variable.

In this task, I'll create a variable called login_status, which is a Boolean that represents whether a user is logged in. Assign False to this variable and store its data type in a variable called login_status_type and display it.

![image](https://github.com/n8som/Assign-Python-Variables/assets/110139109/571c9066-a8ce-4ac8-ad13-d07af15d3999)

The output above shows that the data type of the login_status is bool, which means that login_status stores a Boolean value.

<h2>Conclusion</h2>

What are the key takeaways from this lab?

- Many useful operators in Python help you work with variables.
  - The ```=``` assignment operator allows you to assign or reassign a specific value to a variable.
  - The ```<=``` comparison operator allows you to compare the value of one variable to the value of another.
- The ```type()``` function in Python helps you to determine the data type of an object.
  - If you pass in a variable to ```type()```, it will output the data type of the value stored in the variable.
- The ```print()``` function in Python allows you to display information.
  - It can take in a value directly, a variable that stores a value, or a comparison between variables that evaluates to a Boolean value.


