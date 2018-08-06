# Feed Reader Testing Project
* This is a Udacity project and a part of the Front End Nano Degree course. 
* This Project works with JQuery and Jasmine framework to check the functionalites of the code written in a feedreader app.

## About the tests
### Test Suite - RSS Feeds
* Make sure that the allFeeds variable has been defined and that it is not empty. **_Done by the Udacity team_**
* Ensure that the allFeeds object has a URL defined and that the URL is not empty. **_by looping through the allFeeds object i checked every feed for a URL and check its length_**
* Ensure that the allFeeds object has a name defined and that the name is not empty. **_by looping through the allFeeds object i checked every feed for a name and check its length_**

### Test Suite - The menu
* Ensure the menu element is hidden by default. **_After looking in the inspector i used the 'menu-hidden' class which is used to hide the menu to check that its hidden b default_**
* Ensure the menu changes visibility when the menu icon is clicked. **_I used the click funtion and then checked if the 'menu-hidden' class is removed from the body, used it again and check if the class is added again_**

### Test Suite - Initial Entries
* Ensure when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container. **_Since The loadFeed function is asynchronous, the test should run beforeEach() and done() to ensure the loadFeed runs in the test._**

### Test Suite - New Feed Selection
* Ensure when a new feed is loaded by the loadFeed function that the content actually changes. **_I called the loadFeed function twice with different indexes and compared them to make sure that the content changed_**

## How to run the Project
* You can download the repository by clicking download ZIP on the right of the screen, then extract the zip file to your computer
* Or clone the repository using git:
    ```
    $ [sudo] git clone https://github.com/dinaAbuzied/frontend-nanodegree-feedreader.git
    ```
 * Double-click index.html to open the app in your browser.