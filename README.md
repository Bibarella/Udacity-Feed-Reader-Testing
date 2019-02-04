Udacity - Feed Reader Testing Project

Instructions

This project demonstrates browser based testing using Jasmine. You can run application by downloading as .zip file and run index.html.
The test results appears at the bottom of the page.

ests
1. RSS Feeds:
are defined
It tests to make sure that the allFeeds variable has been defined and that it is not empty.

have URL defined
Loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty

have name defined
Loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.

2. The Menu:
is hidden by default
A test that ensures the menu element is hidden by default.

changes visibility
A test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.

3. Initial Entries:
have at least a single element
A test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.

4. New Feed Selection:
changes content
A test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.