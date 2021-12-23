## SDK Community Policies

Each SDK adopts a set of Community Policies. These include the [E4S Community Policies](https://e4s-project.github.io/policies.html), and may optionally include additional policies taylored to specific SDK needs. Note that in some cases, SDKs choose to adopt a policy that is compatibile with, but more specific than an E4S policy. For example, while E4S requires a member package to have a test suite, an individual SDK may add specifications dealing with the attributes of that test suite, such as the types of tests, coverage of those tests, etc.

The current community policies provide the standards for SDK membership. Member packages are also encouraged to consider future revision policies. Future revision policies require further refinement or planning prior to adoption, but provide information about likely subject areas for future membership criteria. The xSDK has adopted a set of [community policies](https://xsdk.info/policies/) that can be used for a starting point for community policy discussion among SDK developer communities.

A Progress Tracking Card (PTC) outlining an approach to [define and adopt SDK Community Policies](https://docs.google.com/document/d/1ay8n8l8rg8TA92NpajktFA8Ua7p-fKF9RAzG92WQilk/edit?usp=sharing) is available from the [Better Scientific Software](https://bssw.io) Team. Once a team has adopted an initial set of community policies, whether beginning with the E4S policies, or also adopting additional policies, it is important to both refine the policies over time, and document compatibility with the existing policies. After initial adoption, teams are encouraged to consider the applicability and clarity of policies and take appropriate action to ensure the current community policies are effective in the desired ways. In some cases, this may involve working with the E4S community to update E4S policies.

### Documenting Compatibility

In order for the community policies to serve as membership criteria, it is necessary to document compatibility with each policy for every member package. The xSDK has a [system for documenting policy compatibility](https://github.com/xsdk-project/xsdk-policy-compatibility) that consists of having each prospective member package complete a form that describes the compatibility of the package with each policy, and then having an xSDK developer verify compatibility. Any potential compatibility issues or related questions are brought to an xSDK developer meeting. An analogous process for E4S policy compatibility is being developed in consultation with the E4S and [IDEAS-PSIP](https://bssw.io/blog_posts/productivity-and-sustainability-improvement-planning-psip) teams. The goals in developing a new process include improving sustainability and the ability to mine compatibility data, as well as incorporating process improvement.

The current xSDK process uses a static form to collect information. This works for a smaller number of packages, but the new process will store the compatibility information in a database or spreadsheet to allow for easier aggregation, analysis and updating. The new solution is also being designed to incorporate process improvement, both in terms of increasing the level of policy compatibility across products by providing links to associated resources, and by working towards improving the policies themselves. One way the new tool will support policy improvement is by having the form include questions that are not required for policy compatibility currently, but might be added in the future. An example of this is including a question about developer documentation under a policy that currently requires only user and installation documentation. By gathering information about possible new policies or policy revisions, project leadership can make more informed decisions about if or when to make changes.

Two prototypes for a new tool for gathering policy compatibility data have been created. The first was based on the IDEAS-PSIP [Rate Your Project tool](https://rateyourproject.org/). The second is a [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSfWYBBvWT9mi4Fs10vXS40o6bIeooNe7fhKszqjH473FGVozA/viewform?usp=sf_link).

### Improving Compatibility

In partnership with the IDEAS PSIP team, a set of [Progress Tracking Cards (PTCs)](https://bssw-psip.github.io/ptc-catalog/) has been identified that may help package development teams improve compatibility  with E4S Community Policies. In the future, additional PTCs may be developed to support improving compatibility with E4S Community Policies. The current PTCs associated with each of the nine [E4S Community Policies](https://e4s-project.github.io/policies.html) are listed below (policies without associated PTCs are omitted from the list).

#### P4: Documentation

- [Integrated Software Documentation](https://bssw-psip.github.io/ptc-catalog/catalog/IntegratedSoftwareDocumentation.html)
- [End-user Documentation](https://bssw-psip.github.io/ptc-catalog/catalog/UserDocumentation.html)
- [Developer Documentation](https://bssw-psip.github.io/ptc-catalog/catalog/DeveloperDocumentation.html) (This PTC pertains to an area of possible expansion for P4.)

#### P9: Test Suite

- [Adopt Automated Correctness Testing in a Legacy Software Project](https://bssw-psip.github.io/ptc-catalog/catalog/AdoptAutomatedCorrectnessTestingInLegacySoftwareProject.html)
- [Continuous Integration](https://bssw-psip.github.io/ptc-catalog/catalog/ContinuousIntegration.html)
- [Multi-System Performance Testing](https://bssw-psip.github.io/ptc-catalog/catalog/MultiSystemPerformanceTesting.html)
- [Performance Regression Testing](https://bssw-psip.github.io/ptc-catalog/catalog/PerformanceRegressionTesting.html)
- [Test Coverage](https://bssw-psip.github.io/ptc-catalog/catalog/TestCoverage.html)
