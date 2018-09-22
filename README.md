# GitLab-testing

Some CI integration tests with GitLab

## Rationale

GitLab offers a fuller set of services (not all free) for integration tests.

At the free level, it looks like GitLab offers a replacement for Travis CI.

## Testing

So far, tested with:

## Java (Maven)

[Requires a `pom.xml' file.]

* [Alexa Skills Kit - Java](https://github.com/mramshaw/alexa-skills-kit-java)

[Somewhat old and dated - needing updating.]

## Scala

[Requires a `build.sbt' file.]

* [Ad-Tech Scala/Akka exercise](https://github.com/mramshaw/ad-tech)
* [Spray Book Catalog](http://github.com/mramshaw/spray-book-catalog)

[The tests for the `Spray Book Catalog` never did work correctly.]

## Problems

The CI template for Scala does not seem to work correctly.

The attached file is meant to be an update.
