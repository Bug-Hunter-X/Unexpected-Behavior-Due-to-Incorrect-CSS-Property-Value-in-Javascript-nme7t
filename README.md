# Uncommon HTML Bug: Incorrect CSS Property Value

This repository demonstrates a subtle bug in HTML where an incorrect CSS property value prevents an element from hiding as expected. The issue stems from a syntax error in the JavaScript code used to manipulate the element's style.

## Bug Description
The `bug.html` file contains a simple HTML structure with a div element.  A JavaScript script attempts to hide this div using the `style.display` property. However, an incorrect value (`"none!"` instead of `"none"`) leads to unexpected behavior. The div remains visible, even though the intention is to hide it.

## Solution
The `bugSolution.html` file provides a corrected version of the JavaScript code. By simply fixing the syntax error and using the correct value (`"none"`), the div is successfully hidden as expected.

## How to reproduce the bug
1. Open `bug.html` in a web browser.
2. Observe that the div element with the id "myDiv" remains visible on the page, despite the JavaScript attempting to hide it. 

## How to test the solution
1. Open `bugSolution.html` in a web browser.
2. Observe that the div element with the id "myDiv" is correctly hidden.