## Openstack

### Keywords


`Virtual machines` `Bare metal` `Containers` `Infrastructure-as-a-Service` `Orchestration`


Openstack is a platform for the control and administration of resources such as:

- I compute
- storage
- net

instead of a data center.

Openstack is released in July 2019 by ** Rackspace ** and ** NASA ** as an open source project.

Contributors:
 - CANONICAL
 - IBM
 - Redhat
 - Huawei
 - Rackspace

## How does it work?

![openstack from ubuntu page](https://res.cloudinary.com/canonical/image/fetch/f_auto,q_auto,fl_sanitize,w_850,h_250/https://assets.ubuntu.com/v1/2d2a0b2a-what+is+open+stack+diagram.svg)

OpenStack actually uses virtual resources to run a combination of tools.

These tools create a cloud environment that meets the five criteria of the National Institute of Standards and Technology on cloud computing:

- a network
- pooled resources
- a user interface
- the ability to implement
- Automatic control or allocation of resources

## What is Openstack?


>OpenStack is a cloud operating system that controls large pools of compute, storage, and networking resources throughout a datacenter, all managed and provisioned through APIs with common authentication mechanisms. -OpenStack, 2020.


Openstack is an open source cloud IaaS solution that provides users with all the tools necessary to host and manage software infrastructure in the cloud.


From virtualization and servers, to storage and networking, Openstack allows users to manage infrastructure in one place. This services is a pay-by-use.


If infrastructure needs to grow, then paying for the size or scale of the infrastructure, for example, based on number of virtual machines needed is their business model.


Another aspect of Openstack is that it is elastic. This means you can grow or shrink your infrastructure based on need. Also, Openstack is autonomous. Adminsdon't need to create/kill VM's based on need. Openstack takes care of that based on the infrastructures need.


At a big glance, Open stack contains 3 main layers:


- A security layer where you can deploy 1 or many firewalls to protect your infrastructure.
- A load balancer like HAProxy that controls api calls and their destination.
- THe third level contains all the infrastructure nodes, where we run and orchestrate our different backends, API's etc.



![Openstack structure diagram](https://object-storage-ca-ymq-1.vexxhost.net/swift/v1/6e4619c416ff4bd19e1c087f27a43eea/www-assets-prod/openstack-map/openstack-map-v20210201.svg)



### References

- [https://ubuntu.com/openstack/what-is-openstack#:~:text=OpenStack is an open source,share these with the community](https://ubuntu.com/openstack/what-is-openstack#:~:text=OpenStack%20is%20an%20open%20source,share%20these%20with%20the%20community)
- [https://www.redhat.com/es/topics/openstack](https://www.redhat.com/es/topics/openstack)
- [https://www.openstack.org/software/](https://www.openstack.org/software/)
