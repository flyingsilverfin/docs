---
title: Overview
keywords: cloud, deployment, aws
tags: [getting-started, deployment, cloud]
summary: "Deploying Grakn in the cloud"
permalink: /docs/cloud-deployment/overview
---

This section contains an overview of available options regarding Grakn deployments in the cloud.


## Google Cloud Platform

Google Cloud Platform, offered by Google, is a suite of cloud computing services that runs on the same infrastructure that Google uses internally for its end-user products, such as Google Search and YouTube.
Alongside a set of management tools, it provides a series of modular cloud services including computing, data storage, data analytics and machine learning.

Google Cloud Launcher lets you quickly deploy functional software packages that run on Google Cloud Platform. Even if you are unfamiliar with services like Compute Engine or Cloud Storage,
you can easily start up a familiar software package without having to manually configure the software, virtual machine instances, storage, or network settings.

Deploying Grakn on Google Cloud is a straight-forward process, for a guide on how to get started, please visit:

[GC Deployment](https://dev.grakn.ai/docs/cloud-deployment/gc-deployment)


## Amazon Web Services

Amazon Web Services provide on-demand cloud computing platforms on a paid subscription basis. The technology allows subscribers to have at their disposal a fully-fledged virtual cluster of computers,
available all the time, through the Internet. The offered modular services include computing, data storage, data analytics and machine learning.

AWS Marketplace is a digital catalog with thousands of software listings from independent software vendors that make it easy to find, test, buy, and deploy software that runs on AWS. It abstracts the low-level infrastructure
details and offers simple one-click deployments.

Deploying Grakn on AWS follows in a simple manner. Please refer to a guide located here:

[AWS Deployment](https://dev.grakn.ai/docs/cloud-deployment/aws-deployment)


- - - -
MUST BE MERGED
- - - -

---
title: Terms of service
keywords: cloud, deployment, google, eula
tags: [getting-started, deployment, cloud]
summary: "Terms of service"
sidebar: documentation_sidebar
permalink: /docs/cloud-deployment/terms-of-service
folder: docs
---

# Terms of service

By using Grakn in the cloud you agree to the [End User License Agreement](/images/EULA_Cloud.pdf).


- - - -
MUST BE MERGED
- - - -

---
title: Post Deployment
keywords: cloud, deployment, google
tags: [getting-started, deployment, cloud]
summary: "Post Deployment Steps"
sidebar: documentation_sidebar
permalink: /docs/cloud-deployment/post-deployment
folder: docs
---

# Post Deployment


## Support
Deploying Grakn KGMS on Google Cloud comes with our Enterprise Support. Please contact [Support](support@grakn.ai) with your Support ID so we can create your account on our [Support Platform](https://work.grakn.ai/helpdesk).

## Security

The default security settings of Google Cloud Platform offer reasonable amount of security. As the global network is flat, it necessitates in all traffic going over private IPs. As a result of that and the fact that by default all GC deployments are sealed of from external access, significantly less amount of work is needed for setting firewall rules than on other platforms.tThe SSH access to machines either needs to be authenticated via console or CLI.