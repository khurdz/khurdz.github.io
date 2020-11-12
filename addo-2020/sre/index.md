# All Day DevOps 2020 - Site Reliability Engineering

## Technical debt as Pollution

* Replace the `Technical Debt` and its negative connotations with the concept of `Continuous Solution Health`
* There are ~∞ number of root causes for technical debt
* Far cheaper to prevent than clean up or mitigate
* Monitoring is required to ensure compliance
* Accurate accounting is essential
* Technical debt often imposes externalities on third-parties
* [Slides](assets/ADDO-Technical-Debt.pdf)

&nbsp;

## 10 Steps to implement SLO in your Organization

* [Slides](assets/ADDO_2020_SRE_final.pdf)

&nbsp;

## Site Reliability Engineering: Anti-patterns in Everyday Life and What They Teach Us

* Let's start with the basic patterns :
  * Users should never notice an outage before you do
  * Engineer solutions to eliminate classes of errors rather that being satisfied with point fixes
  * Don’t feed the machines with human toil
  * Failure is an opportunity to improve, not to brandish pitchforks
* [Slides](assets/ADDO-2020-SRE-Antipatterns-in-Everyday-Life.pdf)

&nbsp;

## Driving Digital Transformation Through CloudOps and Site Reliability Engineering

* Some thoughts on team topologies
* Liked the progressive and evolving organization over Cloud Operations
  * Mode 1 : Traditional Ops
  * Mode 2 : Distributed Ops
  * Mode 3 : Decentralised Ops
* The so-called four pillars of CloudOps :
  * SRE
  * FinOps
  * GitOps
  * DevSecOps
* [How to get organised and get started](https://cloud.google.com/blog/products/devops-sre/how-sre-teams-are-organized-and-how-to-get-started)
* Measurement is key
  * Differend things to measure depending on if we're talking about infrastructure/platform or product/application
* Get the basics right ; start slow but with confidence !
* [Slides](assets/ADDO_2020-Driving-Digital-Transformation-through-CloudOps-and-SRE.pdf)

&nbsp;

## Cloud as a Commodity: The highest probability of 100% availability

* Interesting antipatterns to resilient architecture
* Some takeaways :
  * "Human errors cause the bigger events"
  * "Environmental events cause AZ outages"
  * "Multi-Cloud with the **CNCF** can be efficient and minimal
operational management overhead"
  * "Pipeline-as-Code ► Orchestration not Automation"
  * "Stop Making Infrastructure Pipelines"
  * "Include IAC / CAC in the delivery (environment delta)"
  * "Environmental requirements are part of the delivery (GitOps)"
  * "One pipeline to rulle them all"
* Have a look at [Harness](https://harness.io/), formerly known as Drone
one pipeline to rule them all
* [Slides](assets/ADDO_2020_SRE_Cloud_as_a_Commodity.pdf)
