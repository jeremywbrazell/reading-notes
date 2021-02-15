# Problem Domain, Objects, and the DOM

## What is a problem domain?
 - A problem domain is the area of expertise or application that needs to be examined to solve a problem. A problem domain is simply looking at only the topics you are interested in, and excluding everything else. It is the area where the problems your application is intended to solve, belong to.

## How To Make the Programming Easier
1. make the problem domain easier
    - accomplish this by cutting out cases & narrowing the focus to a particular part of the problem
1. get better at understanding the problem domain

## Objects
- group together a set of variables and functions to create a model
- cannot have 2 keys with the same name

Ex (object is the curly braces & their content):
Would be referred to as the "hotel object."

```
var hotel = {
    name: 'Quay',
    rooms: 40;
    booked: 25;
    checkAvailability: function() {
        return this.rooms - this.booked;
    }
}
```

### Accessing an Object's Properties or Methods
- done via a dot notation (i.e. - var hotelName = hotel.name;)

## DOM (Document Object Model)
- specifies how a broswer should create a model of an HTML page & how JS can access & update the contents of the page while its in the browser window
- DOM is neither part of HTML or JS
- specifies how the browser should structure the page model using a "DOM tree"
- DOM is called an object model
- DOM is called an API (Application Program Interface)
- the DOM states what your script can ask the browser about the current page, and how to tell the browser to update what is being shown to the user

## DOM Tree
- model of a web page that is stored in the browser's memory
- every element , attribute, and piece of text in the HTML is represented by its own *DOM node*

