# Cypress Web Testing

## what is Cypress?
Cypress is next gen web testing tool that helps developers and QA's to E2E test there applications, Cypress enables to create and run all kinds of tests:

 - [x] Unit Tests
 - [x] Integration Tests
 - [x] E2E Tests
 
 So Basically Cypress can run anything that runs in a browser.
 
 ## Cypress Enviornment
 
 * cypress come up with an in built test runner that allows to run your tests
   * Electron based browser or chrome browser
   * GUI to run tests
   * Dashboard integration
 * dahboard service 
   Dashboaard is kind of CI server for cypress and tests executed from test runner can viewed and compared with previous results.
   
 ## What makes cypress different from other testing tools/frameworks?
 - **Automatic waiting:** Avoids usage of Thread. sleep, Implicit Explit or Fluent waits in code and tries for element till a defined duration of time to load.
 There are different types of [timeouts](https://docs.cypress.io/guides/references/configuration.html#Timeouts) that can be defined in config file of cypress.
 - **Debugging Support:** ypress comes with an inbuilt debigging support using simple [commands](https://docs.cypress.io/guides/guides/debugging.html#Using-debugger) tht helps in error tracing.
 - **Time Travel:** You can view visual impact for each command on just hovering over execution run logs, cypress basically takes snapshots for each run and displays in execution logs.
 - **Cross browser Testing:** Test can run on chrome supported browser and also on firefox.
 - **Network stubbing:** Cypress provides ways to control [network traffic](https://docs.cypress.io/guides/guides/network-requests.html)
 - **Recording of execution**
 - **Spies Stubs Clocks and Ticks:** All these familiar terms from unit tests are supported in cypress to [control](https://docs.cypress.io/guides/guides/stubs-spies-and-clocks.html#Capabilities)
 
 
