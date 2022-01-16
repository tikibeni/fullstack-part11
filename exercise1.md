# 11.1 Warming up

The scenario of the assignment consists of a team of six who have decided to use Java. In the following parts I will
discuss some points regarding the CI given the mentioned basis.

First off as linting, testing and building are common steps in CI, they require their own respective tools to function
depending on the language. For Java perhaps the most common style-checking-tool (linting) is Checkstyle. Testing may
include multiple libraries, which of some are JUnit (for unit testing), Mockito (also for unit testing) and Selenium
(automation tests for browser). A common tool for building is Gradle.

Alternative CI-tools for Jenkins and GitHub Actions are for example: CircleCI (which also supports CD), GitLab and 
Travis CI. There appears to be multiple more alternatives which of I have never heard from before. 

Depending on the size and the level of optimization of the soon-to-be-released project, the cloud-based environment may
be better. As mentioned, the project is nearly ready to release, so self-hosted environment could be a hassle as late as
this part of the process. However, if the team could set up the self-env it could prove to be more stable and efficient
platform as cloud-based environment may not be so efficient. The pieces of information which would affect the decision
would be the total size of the project and the amount of upcoming development after release.
