# What is vRealize Orchestrator?

vRealize Orchestrator is a Client-Server based workflow engine. It allows VMware administrators and IT professionals to automate tasks across the datacenter. The engine is plugin based and comes preloaded with a bunch of extensions for components such as vCenter Server, Active Directory, SQL etc. There are over 200 predefined workflows only as part of the vCenter Server plugin. A workflow can be included in other workflows or run separately. The main tool for interaction with vRealize Orchestrator (vRO) is the vRO client. It's java based standalone application available for multiple operating systems. It serves as a graphical user interface (GUI) to create, run and manage workflows.

## Origin {#origin}

The software was originally developed by Dunes Technologies and called "Virtual Services - Orchestrator", shortened to either VS-O or VSO. The VSO name is still seen in some file names, both in the server and client part. VMware announced that they bought Dunes Technologies on September 11, 2007. With vSphere 4 and vCenter Server 4, the Orchestrator software was now included in the installation and licensing of vCenter Server 4. The product was now called vCenter Orchestrator, shortened to vCO. That name is still very widely used in URLs, file names and other products by VMware.

At VMworld 2014 in Barcelona VMware chose to do a name change on several products, including Orchestrator. This resulted in the name we know today, vRealize Orchestrator.

## Awesome possibilities {#awesome-possibilities}

Thanks to its architecture, vRealize Orchestrator can be easily integrated with many different components in your virtual infrastructure and beyond it. There are plugins allowing you to connect to server systems, storage systems, network devices, cloud providers and more. In the built-in functionality of the product are included plugins for communication with SOAP and REST based APIs. All this creates the possibility to orchestrate tasks across different areas in your datacenter from one single tool. This is a huge advantage as you can control all dependencies and infrastructure automation requirements from one view.

vRO can be configured to operate in clustered mode. This functionality helps vRO to meet the high-availability requirements in an enterprise level IT environment. We will cover this in more details later in this book.