# Pythonic Garage Band

**Author**: Kassie Bradshaw
**Version**: 1.0.0

## Overview

Creating a Garage Band with Object Oriented Programming

----

## Feature Tasks & Requirements

* [x] Use Python classes to model a `Band` made up of different kinds of musicians
* [x] Start with `Guitarist`, `Bassisst`, and `Drummer`
* [x] Make use of a `Musician` base class to handle common functionality which particular kinds of musicians will inherit

----

### User Acceptance Tests

Band Tests

* [x] A `Band` instance should have a `name` attribute which is a string
* [x] A `Band` instance should have a `members` attribute which is a list of instances that inherit from `Musician` base (or super) class
* [x] A `Band` instance should have a `play_solos` method that asks each member musician to play a solo, in the order they were added to band.
* [x] A `Band` instance should have appropriate `__str__` and `__repr__` methods
* [x] A `Band` should have a class method `to_list` which returns a list of previously created `Band` instances

Musician Subclass Tests

* [x] Each kind of `Musician` instance should have appropriate `__str__` and `__repr__` methods
* [x] Each kind of `Musician` instance should have a `get_instrument` method that returns string
* [x] Each kind of `Musician` instance should have a `play_solo` method that returns string.

----

### Stretch Goals

* [ ] See tests marked "stretch" in supplied test suite
* [ ] Make Musician "abstract" - aka an Abstract Base Class
* [ ] Add your own tests

----

## Getting Started

* Use `Poetry` to create a new project named pythonic-garage-band

----

## Change Log

06-16-2021: First submission for lab completed, all required tests passing (no stretch goals)

----

## Credit & Collaboration

* Got a LOT of help from TAs Anthony Beaver & Ben Hill on this one
* Collaborated with Michael Hendricks and Garfield Grant
