# Ruby Bug: Direct Instance Variable Modification

This repository demonstrates a common, yet subtle, bug in Ruby related to the direct manipulation of instance variables using `instance_variable_set` and `instance_variable_get`.  Direct access can bypass any validation or logic associated with accessor methods, leading to unpredictable behavior and making code harder to maintain and debug. 

The `bug.rb` file showcases the issue, while `bugSolution.rb` illustrates how to avoid it by using accessor methods properly.