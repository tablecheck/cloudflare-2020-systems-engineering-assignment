# Systems Assignment

## What is it?

This exercise is a follow-on to the [General Assignment](https://github.com/tablecheck/tablecheck-2020-general-engineering-assignment), you'll need to complete that first.  In this assignment you'll write a program that makes a request to the endpoints you created in the General Assignment. 

## Useful Links

- [General Engineering Assignment](https://github.com/tablecheck/tablecheck-2020-general-engineering-assignment)

## Requirements

### 1. Use one of the specified languages

Choose from among Ruby, Elixir, Python, Go, or Scala.

### 2. Use an off the shelf build tool

Choose something to build your assignment that works with the language you chose (Cargo, Make, CMake etc.).  Include instructions in your readme on how to build and run your program.  Don't check-in binaries, we won't run a pre-compiled binary.

### 4. Create a CLI tool that makes a request to your links page

Your CLI tool should take an argument that is a full URL (--url).  The tool will make an HTTP request to the URL and print the response directly to the console.  Test the CLI tool by specifying the /links URL in your General Assignment and make sure it prints the entire json document with all your links.

Your CLI tool should also allow a --help parameter that describes how to use it.

Feel free to use a library to handle command line argument parsing (getopt etc.).

### 5. Measure how fast it is

Next, add logic to your tool to profile your page.  Add a new argument --profile that takes a positive integer.  Your tool should make that number of requests to your site.  Time the requests and print:

* The number of requests
* The fastest time
* The slowest time
* The mean & median times
* The percentage of requests that succeeded
* Any error codes returned that weren't a success
* The size in bytes of the smallest response
* The size in bytes of the largest response

Include a screenshot of your tool run against your site and another webpage.

Test your tool against your site and some other websites.  Let us know what you find in your readme.  Include outputs for popular sites and your own.  How do we compare?

## Submitting your project

When submitting your project, you should submit your code in a zip file as an email attachment to the hiring manager at TableCheck with whom you've spoken.

Please provide the source code only, a compiled binary is not necessary.
