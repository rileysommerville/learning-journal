# Learning Journal: Week 2

## Learning Activities
After watching the lecture, I watched the demo on using Vagrant and ScotchBox to set up a local Joomla environment. While watching the demo, I read thte documentation for Vagrant and Joomla to better understand how they worked.

To test my set-up, I first hosted my site from prac 1 on the VM server to test. Then, after installing Joomla on the same server, I changed the content and settings of the default theme to match my startup business.

Completed practical: [OverPro (Joomla)](https://sites.glam.dev/overpro/)

## Resources/Links
* [Command-Line Interface on Vagrant](https://www.vagrantup.com/docs/cli)
* [Installing Joomla on Joomla Documentation](https://docs.joomla.org/J4.x:Installing_Joomla)

## Estimated Hours
10 hours

## Content Insights
I learned that while similar in some ways, Docker is a containerisation tool, which separates applications and their runtimes from the machine they run on, while Vagrant is a virtualisation tool, which separates applications and the machines they run on from the physical machines hosting them.

Containers are more lightweight, sharing the resources and kernel of their host OS. This allows them to run with less overhead, but comes with disadvantages. Because the OS is shared, a host kernel vulnerability becomes a vulnerability to all containers on the host, and all containers must run on the same kind of OS.

Virtual machines are heavyweights. They use a hypervisor to divide the physical resources of the host among virtual machines. Because each VM is a completely independent (virtual) machine, it is unaffected by kernel-level problems in other VMs on the host. Each VM runs an entire OS, which comes at the cost of significantly increased resource requirements when compared to containers.

## Career or Employability Insights
I found that watching or seeing a demo that uses one or more tools *while* referring to their documentation makes it much easier to understand: the demo effectively shows an immediate, real-world usage of a selection of features, while the documentation lays out the usage in more general tersm to show how the same process can be applied in other situations.
