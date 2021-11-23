# FSUG Questionnaire

### Access control model

Do you need to run as root? - Developers don't get root or privileged access to hosts or Kubernetes clusters.  Are additional role bindings required?
Consider also linux capabilities, kubernetes privileges, specific security contexts, etc.

### Auditing

How do we find out who is doing what? / In 15 years, how can I find out who did what?
How do we back it up
How do you store your logs and how can people fetch data out of logs?
How do people aggregate data from APIs?

### IAM integration

Can you integrate with centralised directories?  Any local users often need to be tracked in centralised compliance systems, so IAM integration will help speed adoption.  LDAP
What mechanisms are used for authentication? OpenID, Kerberos

### Continuous Delivery/Code Promotion and Release

Networks are often segmented, with complete separation between higher and lower environments. Can code and dev/test and production data be easily exported and promoted, in both a secure and automated manner?

Do you have a digital/software bill of materials?  Can you easily establish provenance for all dependencies for your code?

### Code Review

How is code reviewed for submitted changes?

### Release

How would an end user put together an internal release pipeline for deployment? Do you have specific recommendations, particularly for hotfixes etc?

### Documentation for Devs and Ops

Because there is often a strict separation between dev and ops within FinServ, documentation specifically tailored for ops as well as dev is critical. Do you have this?

### Network Dependencies

Do you have additional dependencies on components such as proxies or service mesh for security or can you support (mutual) TLS (and is this well documented?!)

You may not necessarily be hosted on a public cloud service provider.  What dependencies do you have on internal and public networking, and, if general internet access is required, how can end-users work implement without this?

### Observability

What additional dependencies or components do you have for standard operation or additional functionality?  For example, Prometheus,

### Data Classification and Policy

Data Encryption/data classification:  Some of the data consumed by your project could be PII or sensitive data.  Can this data be encrypted, and can its disk footprint be restricted? (in memory data grids etc.)

### Compliance/Regulations/Audit

Have you gone through CNCF or other threat modeling?

If a security focused product, have you gone through control mappings with any common control frameworks, e.g. NIST 800-53/800-190

### Governance

What is the steering governance of your project?

What is your security vulnerability disclosure policy?

What does your release process for the project look like?

What does your code review process look like?

Every project or product should have an overall governance framework for how changes are made to the projects processes or deliverables.  Can you describe who can make these changes and how they are made?
