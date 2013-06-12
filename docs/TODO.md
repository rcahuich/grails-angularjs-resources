grails-angularjs-resources - TODO
=================================

TODO
----

- finish initial version of the test webapp (more aligned to AngularJS-seed style) ...
- before publishing the new release, set a version higher than the last published in Grails Repository, for example set 1.0.6 ...
- re-generate documentation, and publish in my GitHUB Pages ...

- just after publishing the new release, update docs/links in Grails Plugin web page ...

- update AngularJS to latest stable (currently 1.0.7), update docs, etc ... then re-tag and re-deploy the updated plugin ...
- re-generate documentation, and publish in my GitHUB Pages ...
- check/update install info in main README.md, and test it creating a new Grails webapp from scratch (but then delete it), important ...
- improve documentation with a detailed Tutorial, from a Grails point of view ...


- update dependencies to resources 1.2.x, but in a later plugin release (ex. 1.1.x) ...

- verify if remove angular-manual.js ...
- verify if remove (or move in a test configuration) the angular-scenario.js (and other test-related sources, like angular-mocks.js) ...
	- or verify al least if exclude those files with a dedicated flag (set up in the webapp that uses the plugin) ...

- verify if add a Groovy (or Grails) Script to start a minimal Web Server for publishing static resources only, 
  to simplify/speedup development with static resources only ...


- etc ...

---------------


DONE
----

- fork the original plugin, update dependencies, and do some cleanup ... ok
- add test webapp with reference to the inline plugin ... ok

- in the test webapp start to use resources published by the plugin ... ok

- try to empty "index" module of resources, and see if n2e controller work the same ... ok

- create documentation for the plugin and generate it ... ok
	- in the History put a reference to original author: "Vladimír Oraný", email: "vladimir.orany@appsatori.eu" ... ok


---------------