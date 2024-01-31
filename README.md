# QuackRock FastAPI

We want to learn how to build a REST API with Python. Let's also try to define a meaningful REST API MVC and use it as a starting point for exercises in other languages. In other words, what should a REST API minimally do?

* JSON I/O
* Conventional HTTP usage
* Validation of inputs (request bodies, path and query parameters)
* Meaningful error messages
* A test suite that exercises business logic and the contract, fast
* (Structured) logging with configurable verbosity
* (Structured) access logs that rotate
* Minimal health/status reporting
* Automatically derived documentation

It would be cool to offer add-ons or stretch goals for common use-cases for those who want to explore further:

 * connecting to a database
 * making HTTP calls to third-party services
 * tracing
 * rate limiting
 * authorization
