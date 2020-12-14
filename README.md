# ZeroTrust
Zero Trust Network Architectures
> 
> A vendor-neutral Industry perspective on Zero Trust Networks.
> 
> This collection of contributions provides a high-level overview of Zero Trust referencing
> sources including NIST and NCSC. Industry contributions are aimed at providing application
> related input and use cases.
>
> Please get in touch if you would like to contribute.


# The Zero Trust Concept

First and foremost, Zero Trust is a concept.  It is not at architecture or technology.   It cannot be delivered by a single producy.

The Zero Trust concept works on the principle that networked devices should not be trusted by default, even if they are connected to a managed corporate network. In most modern enterprise environments, corporate networks consist of many interconnected segments, cloud-based services and infrastructure, connections to remote and mobile environments, and increasingly connections to IoT devices. The once traditional approach of trusting devices within a notional corporate perimeter, or devices connected to it via a VPN, makes less sense in such highly diverse and distributed environments. Instead, the Zero Trust Networking approach advocates checking the identity and integrity of devices irrespective of location, and providing access to applications and services based on the confidence of device identity and device health in combination with user authentication.

# Definitions

## NIST Definition(s) SP 800-207

Zero trust (ZT) provides a collection of concepts and ideas designed to minimize uncertainty in enforcing accurate, least privilege per-request access decisions in information systems and services in the face of a network viewed as compromised. 

Zero trust architecture (ZTA) is an enterprise’s cybersecurity plan that utilizes zero trust concepts and encompasses component relationships, workflow planning, and access policies. 

Therefore, a zero trust enterprise is the network infrastructure (physical and virtual) and operational policies that are in place for an enterprise as a product of a zero trust architecture plan.

*  All data sources and computing services are considered resources. 
*  All communication is secured regardless of network location. Network location alone does not imply trust. 
*  Access to individual enterprise resources is granted on a per-session basis. 
*  Access to resources is determined by dynamic policy—including the observable state of client identity, application/service, and the requesting asset—and may include other behavioral and environmental attributes. 
*  The enterprise monitors and measures the integrity and security posture of all owned and associated assets. 
*  All resource authentication and authorization are dynamic and strictly enforced before access is allowed. 
#* ## The enterprise collects as much information as possible about the current state of assets, network infrastructure and communications and uses it to improve its security posture. 

## [NCSC Principles](https://github.com/ukncsc/zero-trust-architecture) (summary version)

### Know your architecture including users, devices, and services 
You need to know your assets – who are your users, what trusted device do you expect them to use, and what services are they likely to need access to? 
### Know your user, service, and device identities
Knowing your users and devices is not sufficient – how are they going to demonstrate they are who they claim to be when on the other end of a network connection? 
### Know the health of your users, devices, and services
Knowing the right user is at the end of the network connection is not sufficient. They may be on a malware-ridden PC (even if it is the right PC). Is that PC up to date with the latest patches and compliant with the anti-malware policy?
### Use policies to authorise requests
Based on the above points, we know the users and devices are trustworthy. But are they authorised to access the service? 
### Authenticate everywhere
All connections need to be authenticated to ensure the request is from a trusted source.
### Focus your monitoring on devices and services
Despite putting in place great protection mechanisms, at some point you will still be attacked, but that attack could now be anywhere – including a cloud service no longer on your network. How are you going to monitor the service to get the earliest possible indication something is awry?
### Don’t trust any network, including your own
Your network is just as likely to be attacked as anyone else’s. 
### Choose services designed for Zero Trust
Fundamentally, if your services adopt the points above, and do them well, you’re going to carry less security risk. 


## Core supporting capabilities
By implication of the NIST and NCSC models, the following capabilities are central to a Zero Trust implementation
* **Risk Assessment**

The need to understand the risks users, devices and services are exposed to, to enable appropriate Zero Trust security controls.

* **Identity Management**

Core to ensuring only trusted users and devices are given access to services

* **Monitoring & Detection**

To feed risk-based access controls.

* **More...**


# Use Cases


