# Midterm Feedback
The midterm feedback will be very similar to what you receive on a weekly basis for the homework, but more specific for each problem in this case.

## Final Score: 38/50


### Step 1: Priest Score Calculation
* **5pts** - Your code computed the correct probability and returned it
* **2pts** - You had a docstring that described what the function was for
  * **(-1pts) You forgot to include the data types of the parameters and the return value as described in class.**
* **3pts** - You had at least three doctests in your docstring

### Step 2: Find a Hospital
* **5pts** - Your code correctly fetched the correct hospital given the inputs using requests
* **2pts** - You had a docstring that described what the function was for
* **3pts** - You had at least three doctests in your docstring

### Step 3: Get the Hospital Address
* **5pts** - Your code correctly fetched the JSON file, parsed it, and looked up the hospital
  * **Note that code like this is redundant `dc_json_response[f'{prev_op_hospital_name}'].  You can just do `dc_json_response[prev_op_hospital_name]`.**
* **2pts** - You had a docstring that described what the function was for
* **3pts** - You had at least three doctests in your docstring

### Step 4: Process List of Patients
* **10pts** - Your code correctly fetched the psv file, looped through it, and ran your other functions
* **2pts** - You had a docstring that described what the function was for
* **(-12 pts) This cell contained the code for Step 3 again rather than the code to process the PSV file**

### Step 5: Compare Results
* **5pts** - Your code looped through all the results and compared them to the provided key
  * **(-3 pts) You had some of the right idea, but your code would always print "successfully match" even if they didn't**
  * **Also, you should have noticed that your code didn't work, and worked on fixing it**

### Extra Credit
* Up to 15 pts based on correctness and quality of the extra credit step
* **(+5 pts) This looks like it probably would have worked, but you didn't demonstrate it with your data**

### Coding Best Practices:
**3 pts** - Was your code readable, efficient, and in line with what we learned in class?
* Good variable names?
* Code written into functions where appropriate?
* Appropriate comments with your code?
* Generally easy to follow and undersand?
