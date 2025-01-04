# Instance Variable Shadowing in Ruby

This repository demonstrates a subtle bug in Ruby related to instance variable shadowing.  When a method has the same name as an instance variable, the method will shadow the instance variable, preventing modification of the instance variable's value unless a setter method is explicitly defined.

The `bug.rb` file contains code demonstrating this issue. The `bugSolution.rb` shows how to correctly define a setter method to address this issue.

This is a less common issue that can be tricky to debug because it doesn't result in a runtime error.