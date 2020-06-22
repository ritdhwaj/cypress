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
 
 ## Cypress-workflow
 
 -**Setup:** Cypress is avilable as an node package and can be installed using any package manager or by downloading installer from official website.
 
     npm install cypress
              or
     npm install cypress --save-dev
     
 -**create tests** Tools come with very simple api to write tests commands a very easy to read and understand. cypress utilizes [mocha](https://mochajs.org/) and [chai](https://www.chaijs.com/) to build powerful and superfast test cases.
 
 -**run tests** Cypress runner or npm commands can be used to run tests on chrome,firefox browsers and as cypress unlike selenium run inside browser tests run in electric speed and gives you full control over tests. 
     <video class="styled__StyledVideo-uf8w4y-2 eaiSAE" poster="/static/debugging-54a2cc93b3d47d9a95c5926200db5462.jpg" playsinline="" autoplay="" loop="" aria-label="Debug Cypress Tests"><source src="/static/debugging-5268ab41c01955e244d85d27af5b8a1b.webm" type="video/webm"><source src="/static/debugging-444bcbb4ee685cd89783d8b1d8bd264b.mp4" type="video/mp4"></video>
     
 -**debug tests for failures:** cypress runner comes with different logs that can be read and utilized for debugging purpose and cypress also supports conditional debugging.
 
     
     
