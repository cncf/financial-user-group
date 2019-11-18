## Scenario: Attacker on the Network

#### Assumptions:
* No network policy in kube-system namespace (this is not configured by default) allowing access from all pods to the kube-system namespace.

* No firewall restrictions in place

#### Details:

This scenario focuses on an attacker with direct network access to the control plane or nodes.  Simulating an internal attacker attempting to compromise the cluster with local cluster access.  As such there are a host of end states depending upon the kill chain.
Note, the majority of these threats can be mitigated with firewalls and appropriate Kubernetes configuration.


#### Full Attack Tree
[Attack Tree - Scenario: Attacker On The Network](pdfs/Kubernetes%20Attack%20Trees%20v1.4.scenario.network.pdf "Scenario: Attacker on Network")