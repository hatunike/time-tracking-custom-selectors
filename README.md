
# Time Events Using CustomSelectorTypes


### The Problem

Many customers want to track time against many different things. Adding all of
the various types of things people want to track time against is difficult.
Additionally adding a new type, might be undesirable for existing users.

### The Solution

Let customers define the things that their time is tracked against. Let them
create any number of new selectors. Let them define what a selector looks like.


### Basic Model

We have a basic setup. A team of teammembers that track their time by selecting 
multiple SelectorObjects (each having a SelectorType).


![alt tag](https://raw.githubusercontent.com/hatunike/time-tracking-custom-selectors/master/basic-model.png)


### Prototype Goals

In order to test the idea, we'll need a basic onboarding process.

* Team Creation
* Add Teammembers
* Create SelectionTypes
* Create SelectionObjects for various types

To aid in onboarding we'll supply 3 optional default types (Projects, Cost Codes
, Equipment)


After onboarding, the user will be able to "clock in" a teammember thus requiring
them to select SelectionObjects for each of the teams SelectionTypes. 
The teammember will then be able to be "clocked out".

Finally, a prototype of viewing a report for any combination of selector types
will be viewable.
