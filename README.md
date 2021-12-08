# Boris-Bikes-Ruby

This is my solo run through of the [Airport Challenge](https://github.com/makersacademy/airport_challenge) which we covered in week 1 of the Makers' Academy. 

I have aimed to solve this challenge in a test driven manner with automated feature and unit tests using RSpec.

## Installation Instructions

Clone the repository from github then change directory into it.

```
$ git clone git@github.com:craigea92/Airport-Ruby.git
$ cd Airport-Ruby
```

Load dependencies with bundle.

```
$ gem install bundle
$ bundle
$ rspec
```

## User Stories

```
As an air traffic controller 
So I can get passengers to a destination 
I want to instruct a plane to land at an airport

As an air traffic controller 
So I can get passengers on the way to their destination 
I want to instruct a plane to take off from an airport and confirm that it is no longer in the airport

As an air traffic controller 
To ensure safety 
I want to prevent landing when the airport is full 

As the system designer
So that the software can be used for many different airports
I would like a default airport capacity that can be overridden as appropriate

As an air traffic controller 
To ensure safety 
I want to prevent takeoff when weather is stormy 

As an air traffic controller 
To ensure safety 
I want to prevent landing when weather is stormy 
```
