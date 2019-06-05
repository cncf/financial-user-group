## Codified controls

### Description:

The project aim is to define a set of controls that can be implemented within Kubernetes to satisfy standard control frameworks.  

This work leverages experience and lessons learned from implementing similar projects across public cloud platforms.

The controls will be implemented along with associated test cases to prove the efficacy of each control.  This creates an SDLC to validate the controls themselves before they are applied to a Kubernetes installation.  The main control checks can be executed as part of the infrastructure SDLC used to deploy the platform or configured installations post deployment.  

The system will also provide a normalised output to allow audit teams to view and query the control data.  This could then be archived and used to become part of an audit.

### Outcome:
Automated system to assist in confirming compliance with appropriate controls along with an SDLC to validate the efficacy of those controls..  

### Next Steps:
* Select initial audit standard
* Identify stakeholders & interested parties 
* Define set of controls applicable to specified standard in Kubernetes
* Define BDD test cases required to prove efficacy of each control
* Merge initial set of controls that satisfy control test cases
* Implement controls SDLC to validate control efficacy
