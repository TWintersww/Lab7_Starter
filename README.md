Name: Evan Wu

1. Within a Github action that runs whenever code is pushed. This creates a universal check such that everybody's pushed code is checked against tests for errors. Developers also have one less thing to worry about in terms of if their tests are up-to-date if we automate the testing process instead of having developers run local tests before pushing.

2. No. End to end testing is intended to see if UI components on webpages work as expected by having a testing library interact with a webpage. Checking functions for correct output does not require these components, just an assertion is enough.

3. Navigation mode analyzes how a webpage is in its initial load, whereas snapshot searches for accessibility issues for a page in its current state. Snapshot can analyze a page in any state whereas navigation only focuses on the launch screen. Navigation mode provides a performance report, whereas snapshot doesn't care about performance, only structure.

4. First, we could add a viewport tag to adapt screen sizing to users on mobile or other non-desktop devices. Second, we can add a lang attribute to the html element so search engines know which language the site is in. Third, the document could use a meta description to optimize search engine recommendations to prospective site visitors.


