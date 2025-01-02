# Uncommon HTML Bug: Incorrect getElementById Usage

This repository demonstrates a common mistake when using `getElementById` in JavaScript within an HTML context. The bug arises from an incorrect selector string used when trying to get an element with the ID '#myDiv'. 

## Bug Description
The provided HTML code includes a script that intends to hide a div element with the ID 'myDiv'. However, it incorrectly uses '#myDiv' as the selector within `getElementById`. This causes the script to fail and the div element remains visible.

## Bug Solution
The corrected code removes the '#' from the selector string, allowing `getElementById` to successfully find and hide the element.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe that the text inside the div remains visible. 
4. Open `bugSolution.html` to see the corrected code and observe that the text is hidden.