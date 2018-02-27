> Disclaimer: This is a fork of the great [Deis Slugrunner](https://github.com/deis/slugrunner) maintained by `LuizaLabs` and used on [Teresa](https://github.com/luizalabs/teresa) project.

# Slugrunner

Teresa is an open source Platform as a Service (PaaS) that adds a developer-friendly layer to any [Kubernetes](http://kubernetes.io) cluster, making it easy to deploy and manage applications.

We welcome your input! If you have feedback, please [submit an issue][issues]. If you'd like to participate in development, please read the "Development" section below and [submit a pull request][prs].

# About

The slugrunner downloads a [slug](https://devcenter.heroku.com/articles/slug-compiler) from a specified [S3 API compatible server][s3-api] and uses the [Procfile](https://devcenter.heroku.com/articles/procfile) mechanism to run the application.

This component is usually launched and uses inside of Teresa [PaaS](https://en.wikipedia.org/wiki/Platform_as_a_service), but it is flexible enough to be used as a pod inside any Kubernetes cluster.

# Development

The Teresa project welcomes contributions from all developers. The high level process for development matches many other open source projects. See below for an outline.

* Fork this repository
* Make your changes
* [Submit a pull request][prs] (PR) to this repository with your changes, and unit tests whenever possible.
  * If your PR fixes any [issues][issues], make sure you write Fixes #1234 in your PR description (where #1234 is the number of the issue you're closing).
* The Teresa core contributors will review your code. After each of them sign off on your code, they'll comment your PR with `LGTM`. Once that happens, the contributors will merge it.

[issues]: https://github.com/luizalabs/slugrunner/issues
[prs]: https://github.com/luizalabs/slugrunner/pulls
[s3-api]: http://docs.aws.amazon.com/AmazonS3/latest/API/APIRest.html
