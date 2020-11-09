# Systems Assignment

## What is it?

This exercise is a follow-on to the [General Assignment](https://github.com/tablecheck/tablecheck-2020-general-engineering-assignment).  In this part, you'll write a program that makes a request to the endpoints you previously created.

## Useful Links

- [General Engineering Assignment](https://github.com/tablecheck/tablecheck-2020-general-engineering-assignment)

## Requirements

### 1. Use any programming language you like.

Our team is most familiar with Python, Ruby, Go, or Elixir but you are more than welcome to use any language you are proficient in.

### 2. Use an off the shelf build tool

Choose something to build your assignment that works with the language you chose. Please include instructions in your README with how to build and run your program.

### 3. Create a CLI tool that makes a request to your links page

Your CLI tool should take an argument that is a full URL (--url). This could be, for example: https://google.com/.  The tool will make an HTTP request to the URL and print the response directly to the console.  Test the CLI tool by specifying the /links URL in your General Assignment and make sure it prints the entire json document with all your links.

Your CLI tool should also allow a --help parameter that describes how to use it.

Feel free to use a library to handle command line argument parsing (getopt etc.).

### 4. Measure how fast it is

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

You made it this far! Thank you so much for your time and effort completing this take-home project. Now it's time to hand it in and relax.

When submitting your project, you should submit your code as a GitHub repository link. Please send this to the hiring manager at TableCheck with whom you've spoken.

Again, congratulations and thank you! :tada:
