# Cloud Network and Access Control Architecture

**An AWS networking and access-control coursework report for an internal application.**

The report by **Aswin T. J.** describes VPC segmentation, public and private subnets, routing, EC2 placement, and security-group restrictions. It discusses common misconfigurations and their correction through least-privilege access rules.

## Repository contents

| Artifact | Contents |
| --- | --- |
| [Project report](Aswin.project.docx) | Objectives, requirements, implementation workflow, and conclusions |

## Topics covered

- Separation of application workloads and administrative access.
- Internet gateway and route-table configuration.
- Source- and port-based security-group restrictions.
- Reducing unrestricted administrative exposure.
- Comparing insecure and corrected network configurations.

## Review the project

Download the report and open it in Word or another compatible document viewer. This repository contains documentation, not a runnable application or reproducible infrastructure deployment. No Terraform, CloudFormation, or automated validation suite is included.

## Scope and next steps

The report records the coursework design and workflow; it does not demonstrate that a cloud deployment remains active. A reproducible extension would add an architecture diagram, infrastructure definitions, and explicit connectivity tests. Public application access and private administrative access should be specified separately when implementing the design.

**Author:** Aswin T. J. · B.E. CSE (Cyber Security), SKCET.
