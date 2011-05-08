# RMU SESSION 7 EXERCISE 1

If in doubt about how to submit, see SUBMISSION_GUIDELINES file.

In this exercise, we'll be wrapping command line applications to
make them feel like ordinary Ruby libraries. Please keep the following
guidelines in mind while working on this problem. 

## GUIDELINES

* You can choose any freely available command line application you'd like to
  wrap, although ideally it will NOT be written in Ruby.

* Your goal is to create a library that wraps the target command line 
  application to do something interesting. You do not necessarily need to expose
  all of the features or options from the underlying command line application,
  but your wrapper should be featureful enough to be useful.

* For simple things, you may be able to get away with ordinary system calls,
  for more complex interactions, you may need to use popen() or the open3
  standard library, or some other third party tool.

* You should provide tests or at least some good examples to demonstrate how
  your library is meant to be used.

* It's not absolutely essential to avoid reinventing the wheel, but you get some 
  bonus points for wrapping an application that either hasn't already been
  wrapped, or hasn't been wrapped in the way you plan to.

* Be sure to announce what application you plan to wrap to avoid duplication.
  Two students may not wrap the same application unless there is very little
  overlap between their ideas.

## EXAMPLES

- A library that wraps the OS X 'say' command with an API that allows direct
  audio output, output to file in different formats, input from a string or 
  a file, and selection of voices.
  
- A library that the command line Go game engine gnugo and makes it possible
  to play a game through a Ruby API, capturing the board output and converting 
  it to Ruby objects.

## QUESTIONS?

Hit up the mailing list or IRC. RMU exercises are left deliberately open ended,
and often benefit from some discussion before, during, and after you work on
them. 
