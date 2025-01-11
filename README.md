# Uncommon HTML Bug: Premature DOM Access

This repository demonstrates a subtle bug in HTML/JavaScript related to accessing a DOM element before it's fully parsed by the browser.  Attempting to manipulate an element's properties before it exists will result in an error.  The solution involves ensuring the element exists before attempting to modify it.