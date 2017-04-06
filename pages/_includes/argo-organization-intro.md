This profile sets minimum expectations for the [Organization] resource to searching for and fetching a Organization associated with a patient or provider. It identifies which core elements, extensions, vocabularies and value sets **SHALL** be present in the resource when using this profile.


##### Mandatory Data Elements and Terminology

The following data-elements are mandatory (i.e data MUST be present). These are presented below in a simple human-readable explanation.  Profile specific guidance and examples are provided as well.  The [**Formal Profile Definition**](#profile) below provides the  formal summary, definitions, and  terminology requirements.  

**Each Organization must have:**

1.  A name
1.  An identifier
1.  A status of the organization
1.  A list of contact information
1.  Endpoint information


**Profile specific implementation guidance:**

* A server *SHALL* support the [_include](http://build.fhir.org/search.html#include) parameter when retrieving a Location resource.


[Organization]: http://build.fhir.org/organization.html

##### Examples

- [Organization-1](Organization-example-organization-1.html)
- [Organization-2-with-Endpoint](Organization-example-organization-2.html)
