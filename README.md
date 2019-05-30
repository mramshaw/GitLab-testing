# GitLab-testing

Some CI integration tests with GitLab

## Rationale

Compared to GitHub, [GitLab](http://gitlab.com/) offers a fuller set of services
(not all free) for integration tests.

At the free level, GitLab offers a replacement for [Travis CI](http://travis-ci.org/).

GitLab is fairly opinionated with regard to workflow, this is my attempt to
check it out.

GitLab describes itself as:

> a single application for the entire software development lifecycle. From
> project planning and source code management to CI/CD, monitoring, and security.

From http://about.gitlab.com/

## Testing

So far, tested with:

## Go

* [Radix Trie](http://github.com/mramshaw/radix-trie)

[The `go` template uses an interesting approach to dependency management.]

* [GitLab](http://gitlab.com/mramshaw/gitlab)

[This was created in GitLab rather than migrated from GitHub.]

## Java (Gradle)

* [AWS Lambda Sample - Java](http://github.com/mramshaw/aws-lambda-sample)

[Not really suitable for testing integration as it mainly works via manual testing.]

## Java (Maven)

[Requires a `pom.xml` file.]

* [Alexa Skills Kit - Java](http://github.com/mramshaw/alexa-skills-kit-java)

[Somewhat old and dated - needing updating.]

## Scala

[Requires a `build.sbt` file.]

* [Ad-Tech Scala/Akka exercise](http://github.com/mramshaw/ad-tech)
* [Spray Book Catalog](http://github.com/mramshaw/spray-book-catalog)

[The tests for the `Spray Book Catalog` didn't work correctly to start with.]

## Problems

The CI template for Scala does not seem to work correctly.

The attached file is meant to be an update.
