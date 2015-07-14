# Block 0

## Session Dates

* Monday 2/9
* Tuesday 2/17
* Monday 2/23

## Subjects

### Building a Binary Search Tree with Jeff

Binary search trees are a great opportunity to explore a fundamental CS data
structure, practice TDD and unit and integration levels, and think about algorithmic
complexity. In the first session we'll briefly go over how BSTs work, then create
working pairs to begin building. In the second session we'll check-in on progress
and experiment with the best and worst case scenarios for input data.

### iOS Fundamentals with Steve

In this session, we'll cover the fundamentals of the Swift programming language as well as some of the very basics of building a application using Apple's frameworks. If you're planning on attending this session—make sure you install Xcode at lunch—you can find it on the Mac App Store.

### Profiling the Performance of Ruby Code with Horace

Performance is an important part of good software engineering, but it's also easy
to complicate our code unnecessarily in the name of speeding it up. So how do we know
which improvements are worthwhile? In this elective we'll introduce some tools for
measuring the performance of our ruby code and pinpointing the portions that actually
need improvement. The first session will focus on ruby's built-in Benchmark library and
the powerful ruby-prof gem. The second session will look at some more extensive
"all-in-one" application profiling tools which can be useful for web apps.

### XYZ with Jorge

### Building a Gem with Josh Cheek

Material is [here](https://github.com/JoshCheek/elective-building-a-gem)

We're going to make a gem that has a program you can invoke on the commandline.
You'll give it a git repository and it will tell you how many non-blank lines
are in each file, as well as the total for the whole repository.

We'll cover:

* Working with gems
  * What libraries and gems are
  * The structure of the .gem format
  * How to install a gem you are building
  * How to version a gem
  * How to publish a gem
* How to make an executable
  * Where it goes, what it does
  * The `$PATH`
  * File permissions
  * Shebangs
  * The `$LOAD_PATH`
  * How to get command line arguments
  * How to print output and errors
* How to make the code
  * Where it goes
  * Load path namespacing
  * Constant namespacing
  * Mapping class names to file locations
* Test Driving our gem
  * Start with an acceptance/integration test
    * to give us confidence that we haven't broken anything
    * and flexibility to iterate and make changes
  * Using fixtures
  * Dropping down to unit tests
    * to get feedback about our design
    * to make it easy to verify features do what we expect, with minimal overhead
    * the thought process of writing tests
  * Our testing will follow what's I do in reality.
    I treat all religions with iconoclasm, TDD is no exception --
    we will test our code this way because it is incredibly effective,
    not because someone will shame us if we don't.

You will need to be comfortable working with basic Ruby classes like
arrays, enumerables, and strings -- I don't want our time to be eaten up
tripping over Ruby.

### Fun with Hue Bulbs with Josh Mejia

Interactions between code and devices are becoming more and more prevalent and the possibilites are endless.
Read about the [Internet of Things](http://en.wikipedia.org/wiki/Internet_of_Things) for examples.
We'll start to dabble with these interactions by writing code that parses input from one source and
communicates its output using color by talking to [Hue Bulbs](http://www2.meethue.com/en-us/).
What you decide to build will be up to you. Some example apps if you need some inspiration:

1. Parse weather data provided by an API. Based on the temperature, change the color of the Hue Bulb.
2. Same as 1, but instead of using an API, use an Arduino to measure the temperature.
3. Let everyone around you see how great your test coverage is by changing color based
on measurements by Simplecov.
4. Same as 3 but for code quality using Hound.

# Block 1

## Session Dates

* Monday 3/2
* Monday 3/9
* Monday 3/16

## Subjects

### Arduino Experiments with Jeff

Arduino's are for more than blinking LEDs. In this sequence of three sessions we
will (a) brainstorm a handful of small, real projects and (b) break into teams
to actually implement them. Word on the street is that Steve dreams of a monitor
system that lets you know which bathrooms are available.

### XYZ with Steve and Horace

### XYZ with Jorge

### Using Jekyll to Create a Blog Hosted on Github Pages with Rachel

Jekyll is a Ruby gem that provides a (relatively) simple way to build a blog using templates, partials, markdown, code snippets, etc. In this elective, we'll learn how to generate a Jekyll project, preview content on localhost, and publish your project on Github Pages.

### Build a Webserver with Josh Cheek

In this class, we will understand the web and HTTP
by building a webserver.

You will need to have familiarity with classes, methods, and string manipulation.
You might get to work with blocks, unless I can think of an elegant way to avoid them.

We will see what makes a request a GET or POST request,
what headers and cookies actually are, where HTML fits
into all of this, how a redirect works, etc.

As usual, you'll get my flavour of TDD and design.

### ActiveRecord Golf with Josh Mejia

Compete against peers using profiling tools and see who can get the fastest
response times by improving ActiveRecord queries. We'll keep a running score that
will carry across all three weeks.

By the end of the three weeks you should have a solid understanding of:

* `has_many :through`
* polymorphism
* self-referential associations

# Block 3

## Session Dates

* Monday 3/30
* Monday 4/6
* Monday 4/13

## Subjects

### Building Servers with Jeff

Did you know Turing has about a dozen physical servers? In this series of sessions
we'll (a) take them apart and explore the physical components, (b) get them racked
and running, (c) figure out how to install Linux and get the basic OS setup, (d)
configure them to run web servers and the other tools we need for web applications.

### Data Visualization with JavaScript with Steve

Let's take some data and make some JavaScript and make some awesome visualizations. In this elective, we'll be working with D3.js and other libraries to parse, organize, and—ultimately—visualize our open data.

### XYZ with Horace

### XYZ with Rachel

### Build a Webserver with Josh Cheek

Continue building a webserver.

### Learning Python the Hard Way with Josh Mejia

*Beginner Friendly*

This will be a study group style elective. Josh doesn't know Python but wants to learn. If you want to learn Python too, you should join us. We'll work through [Learn Python the Hard Way](http://learnpythonthehardway.org/book/). Purchasing the book is encouraged but not required.

Check out [this article](http://www.scriptrock.com/articles/python-vs-ruby) for a comparison to Ruby.

# Block 4

## Session Dates

* Monday 4/20
* Monday 4/27
* Monday 5/4

## Subjects

### Sampling Elixir with Jeff

Dave Thomas said that Elixir is the programming language he's most excited about
right now. It's a pretty different paradigm from Ruby. Let's get together to
see what we can figure out, using Dave's book as our guide.

### XYZ with Steve

### XYZ with Horace

### XYZ with Rachel

### Build a Webserver with Josh Cheek

Continue building a webserver.

### XYZ with Josh Mejia
