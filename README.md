# Adoption Website

## Setup

**Your project should have:**
```
|- db
    |- pets.json
    |- types.json
|- javascripts
    |- events.js [Attaching all event listeners]
    |- data.js [Error and success functions for XHR]
    |- main.js [Entry point/start application]
    |- pets.js [XHR call for pets.json]
    |- types.js [XHR call for types.json]
|- index.html
|- main.css
```

**Install via CDN:**

- jQuery
- Bootstrap

**Browserify and Grunt:**

- Use npm to install Browserify, and any other packages you need to compile your modules.
- Make sure you have the Grunt task running that will build the distribution bundle file.

## Requirements

- As a user, I want to see a listing of all available pets. Each pet should have a card that has all this data:
```
Image
Name: xxx
Color: xxx
Special Skill: xxx
Type of Pet Label:
Type of Pet Description
```
- As a user, I want to see 3 category(type) buttons printed at the top of the page, along with their descriptions.
- I want to be able to click one of the 3 buttons, then only the cards that are in the category should show.
- There should be some way for the user to unfilter the results.

## Technical Requirements

- You should be using Bootstrap to achieve the mockup
- You should be using Browserify
- Your code should be clean and readable, with single responsibility principle
