# Uncommon HTML Error: Typo in getElementById

This repository demonstrates a simple, yet easily overlooked, error in JavaScript when interacting with the DOM.  The code contains a typo in the `getElementById` method, a common mistake for those new to JavaScript.

## Bug Description

The bug is a simple typo in the `getElementById` method. The code uses `getElementByIdx` instead, which results in a `TypeError` because the incorrect method does not exist.

## Solution

The solution is to correct the typo.  Change `getElementByIdx` to `getElementById` to correctly access the element.

## How to Run

1. Clone this repository.
2. Open `bug.html` in your web browser. You should see a JavaScript error in the console.
3. Open `bugSolution.html` in your web browser. This corrected code will successfully modify the text within the div element.
