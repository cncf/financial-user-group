## Access Sensitive Data

#### Assumptions:
* Assume network access to the cluster

* Assumes no specific security controls in place

* SDLC is out of scope for this attack tree

* Direct exploitation of a backend following the compromise of the application credential is out of scope.
#### Details:

Major approaches in this section centre around being able to read secret data from the cluster directly by exploiting misconfigured RBAC permissions.  Other approaches include viewing sensitive data stored within logs and eavesdropping on network traffic.

#### Full Attack Tree:
[Attack Tree - Access Sensitive Data](pdfs/Kubernetes%20Attack%20Trees%20v1.4.sensitive.data.pdf "Access Sensitive Data")