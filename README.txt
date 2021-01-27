Used JMeter version 5.4.1.
In order to run tests we first need to open JMeter -> JMeter 5.4.1\apache-jmeter-5.4.1\bin\ApacheJMeter.jar
When it's open, we need to add test plan (curently the are 3: Issue Creation.jmx, Playground Creation.jmx and Use Case Creation.jmx) -> File-Open-JMeterPlans

Issue Creation.jmx: Threads (users) = 3, means after running tests the same issue will be created 3 times
Playground Creation.jmx: Complete project flow will be created. As I explained for Selenium tests, for JMeter I added ".jmx" next to the text (e.g. Selenium.jmx) 
Use Case Creation.jmx: Threads (users) = 3, means after running tests the same use case will be created 3 times

To run tests within one plan select green pointer and check results in "View Results Tree" node. If all green go to app and check what is created.

Note: Playground form (https://qa-sandbox.apps.htec.rs/projects) is intentionally left empty (nothing created) and after starting the tests everything will be created (what, explained in use cases). 
