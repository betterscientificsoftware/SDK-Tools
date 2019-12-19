# Product Release and Deployment Maturation

An important aspect of SDKs is to release, and often deploy, a useful collection of software. The quality of both the individual product releases and the interoperability between software inside and outside of the SDK are critical. Attaining and maintaining this interoperability are both challening activities. Product development teams commonly need to deal with producing software releases and with versioning issues associated with the product's direct dependencies. While these alone are challenging activities, in the context of an SDK, as well as all of E4S in the case of ECP ST, it is necessary to coordinate interoperability, as well as dependency versioning issues, with a much larger group of stakeholders. In the end, this degree of coordination can only be achieved through SDK or E4S-level testing.

There are many factors that go into the policies associated with this kind of many product testing. For example:

1. What response time is required of product teams for issues associated with each type of failure?
  - Platform
  - Type (configure/build/test, etc)

2. What is the process for modifying the supported version(s) of a dependent piece of software?
  - What happens if a product fails to support a new version?

These and other decisions must be negotiated by the SDK development teams with the approval of funding sources. These are SDK-centric or E4S-centric issues. 

From the product perspective, there are steps that can be taken toward improving and maintaining release readiness. Some of these steps require a certain amount of maturity on the part of the SDK or E4S, for example, participating in higher-level CI testing, while others do not. The [Better Scientific Software](https://bssw.io) team has developed a [Software Technologies Release Readiness Progress Tracking Card](https://docs.google.com/document/d/1c1v7salWQBRJ2XOJxqI7W8pjSdzn0FHwGe-08na-A8I/edit?usp=sharing) to assist teams with preparing to participate in ECP ST software release and deployment activities, as well as sustain release readiness into the future. Over time, lower-level resources will be added focused on the implementation of individual progress tracking card steps.
