# Pythonic Garage Band

**Author**: Kassie Bradshaw
**Version**: 1.0.0

## Overview

Creating a Garage Band with Object Oriented Programming

----

## Feature Tasks & Requirements

* [ ] Use Python classes to model a `Band` made up of different kinds of musicians
* [ ] Start with `Guitarist`, `Bassisst`, and `Drummer`
* [ ] Make use of a `Musician` base class to handle common functionality which particular kinds of musicians will inherit

----

### User Acceptance Tests

Band Tests

* [ ] A `Band` instance should have a `name` attribute which is a string
* [ ] A `Band` instance should have a `members` attribute which is a list of instances that inherit from `Musician` base (or super) class
* [ ] A `Band` instance should have a `play_solos` method that asks each member musician to play a solo, in the order they were added to band.
* [ ] A `Band` instance should have appropriate `__str__` and `__repr__` methods
* [ ] A `Band` should have a class method `to_list` which returns a list of previously created `Band` instances

Musician Subclass Tests

* [ ] Each kind of `Musician` instance should have appropriate `__str__` and `__repr__` methods
* [ ] Each kind of `Musician` instance should have a `get_instrument` method that returns string
* [ ] Each kind of `Musician` instance should have a `play_solo` method that returns string.

----

### Stretch Goals

* [ ] See tests marked "stretch" in supplied test suite
* [ ] Make Musician "abstract" - aka an Abstract Base Class
* [ ] Add your own tests

----

## Getting Started

* Use `Poetry` to create a new project named pythonic-garage-band

----

## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. This is also an area which you can include any visuals; flow charts, example usage gifs, screen captures, etc.-->

----

## API
<!-- Provide detailed instructions for your applications usage. This should include any methods or endpoints available to the user/client/developer. Each section should be formatted to provide clear syntax for usage, example calls including input data requirements and options, and example responses or return values. -->

----

## Change Log

06-06-2021:
