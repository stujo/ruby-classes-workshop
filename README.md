#ruby-classes-workshop
=========

__NOTE: This lab comes with a complete solution, you are an adult and you are here to learn, just copying the solution will not help you learn. It is provided so that you can review it AFTER you have completed the lab (with some struggles) but it's up to you. I can tell you that just copying the lab will be a waste of you time :)__

#How to use this lab

__Congratulations! You've been hired as a programmer at a prestigeous university!__

Unfortunately for you the programmer who was here before didn't know about Ruby classes and coded the whole application using Hashes

The boss has hired you for your Ruby Objects and Classes chops and wants your to rewrite the app using classes!

Luckily for you the app works just fine, you can run it like this:

```
ruby students_as_hashes.rb 
```

More good news! Your friendly coworker has written a bunch of test cases which will  check that your rewrite is on track

The job is split into 3 steps each in it's own folder

To Start go into the `000-step` folder and run `ruby 'student.rb'`

And you will see this:

```

ruby student.rb 

FAILED!  : Student class isn't implemented

```

Make changes to the student.rb file until the step is complete

Then move to the next folder 

```
cd ../001-step
```
and continue the process in each step folder until you are done!

```
ruby student.rb 

FAILED!  : fullName isn't implemented, did you use def fullName
FAILED!  : calculateGPA isn't implemented, did you use def calculateGPA
FAILED!  : An error occurred NoMethodError : undefined method `fullName' for #<Student:0x00000102800130>
student.rb:77:in `runTests'
student.rb:97:in `<main>'
```

The 999-solution folder provides you with a complete solution

```
ruby 999-solution/student.rb 
Barry White : 3.75
Donna Summer : 4.0
Skrillex  : 3.9
```
