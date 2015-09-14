---
title: "REST API specification formats"
permalink: /pubapis_rest_specification_formats/
course: "Documenting REST APIs"
type: notes_docapis
weight: 5.3
---
{% include notes.html %}
In an earlier lesson, I mentioned that REST APIs follow an architectural style, not a specific standard. However, there several REST specifications that have been formulated to try to provide better documentation, tooling, and structure with REST APIs. The three most popular REST API specifications are as follows:

* [Swagger](http://swagger.io/)
* [RAML](http://raml.org/)
* [API Blueprint](https://apiblueprint.org/) 

## Should you use a solution

In a [survey on API documentation](http://idratherbewriting.com/2015/01/06/api-doc-survey-automating-rest-api-documentation/), I asked people if they were automating their REST API documentation through one of these standards. Only about 30% of the people said yes. 

Keep in mind that these specifications just describe the reference endpoints in an API, for the most part. While the reference topics are important, in my documentation projects, the bulk of the documentation is actually not the reference topics. There is a tremendous amount of documentation about how to configure the services that use the endpoint, how to deploy the services, what the various resources and rules are, and so forth. 

If you choose to automate your documentation using one of these specifications, it likely will be a separate site that showcases your endpoints and provides API interactivity. You'll still need to write a boatload of documentation about how to actually use your API. 

{{tip}} For an excellent overview and comparison of these three REST specification formats, see <a href="http://nordicapis.com/top-specification-formats-for-rest-apis/">Top Specification Formats for REST APIs</a> by Kristopher Sandoval on the Nordic APIs blog.{{end}}