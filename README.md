# F/E Challenge Assignment

## WHO

The ideal candidate will be proficient with JavaScript, will have written a few single page-style web apps, and will be proficient building something using the Backbone library. There will be an expectation that the contractor will be able to contribute approximately 20-30 hours of work per week and will feel comfortable interfacing with internal development staff through chat, phone, etc.

## WHAT

This paid challenge assignment is designed to help us assess your proficiency building a small system using JavaScript and Backbone. We'd like you to implement what you see in the mockups; it needs to be able to:

1. Parse some entered JSON to a Backbone collection
1. Allow the user to edit models in the collection, if desired
1. Allow the user to go back to beginning of workflow and re-parse the entered JSON
1. Allow the user to go back and forth between steps in the workflow

It contains a few challenging problems (nonlinear workflows, nested views, state-maintenance, etc.), but shouldn't take much longer than a day to complete. The finalized product does not need to look good; we're going for function rather than presentation.

## HOW

A PDF containing mockups and a description of workflow has been included in this project (challenge.pdf). Blue arrows indicate view/context changes, and yellow arrows indicate "gotcha"-type notes that you'll want to pay attention to.

### Several libraries have been included; please don't use anything not in this list:

1. Backbone
1. Marionette
1. jQuery
1. qTip2
1. Underscore
1. JSON2

### Two sample input files have also been included:

1. input_invalid.json - should throw an exception when parsing
1. input_valid.json - valid input; should trigger the UI states shown in the mockups

## NOTES

### Paste in some data screen

1. Clicking "Skip Edits" or "Import and Edit" in "Paste in some data" context ALWAYS triggers a parse of what's currently in the text-area.

### Edit data screen

1. Editing a fruit name and then cicking "Back" will not affect a change in the original text displayed in the "Paste in some data" context
1. Edits that the user has made should persist after clicking "Back" from the "Results" page

### Results screen

1. The "Back" button will do different things depending on the last context the user was viewing.
1. Nothing will be added to your original list of fruits until the "Finished" button is clicked



    
    
