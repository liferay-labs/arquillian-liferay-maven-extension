Maven Deployment Scenario Extension
========================================================

![Build Status](https://travis-ci.org/liferay-labs/arquillian-liferay-maven-extension.svg?branch=master)
![codecov.io](https://codecov.io/github/liferay-labs/arquillian-liferay-maven-extension/coverage.svg?branch=master)

Tomcat setup:

should setup user and password in tomcat-users.xml, deploy the manager application

## Testing Pull Requests
If you want any pull request you receive to be automatically tested by Travis CI, please set up your job directly in Travis.

- Go to [http://travis-ci.org/profile](http://travis-ci.org/profile)
- Enable Travis for arquillian-extension-liferay Github repository
- Click on the Settings icon.
- Enable 'Build pull requests' option element.

With those simple steps pulls will be tested against one of the most popular Open Source CI systems nowadays.

## Keeping Travis CI up-to-date
Anytime you add a dependency on the build system, verify that it is properly configured in the Travis CI descriptor, the [.travis.yml](.travis.yml) file, so that pulls there don't get broken.
