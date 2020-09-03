---
title: Users
slug: users
excerpt: Learn the concept behind Ai Training users
section: Concepts
order: 2
---
## Definition

The **users** of the AI Training platform are simply your Public Cloud
users that you can create in your management interface. To give access
to AI Training to any of your user you need to grant them the role **AI
Training Operator**. Then you can use this user credentials to
authenticate.

The AI Training includes the OVHcloud Object Storage as a persistent
storage solution for your [data](../data). To use these features the
user needs to be granted the role **Objectstore Operator** since it
implies read/write access to the Object Storage.

### Roles

There are 2 available roles :

-   `AI Training Operator` : Grants access to **AI Training**.
-   `Objecstore Operator` : Grants read/write access to the OVHcloud
    Object Storage, required to use **data** synchronization features.

## Considerations

-   Access to **AI Training** can be revoked at all moment by deleting
    the user or removing its **AI Training Operator** role.
-   To be able to use Object Storage synchronization features make sure
    that the user has the **Objectstore Operator** role

## Going further

-   You can check the [OVHcloud documention on how to submit a
    job](../submit-job).

## Feedback

Please send us your questions, feedback and suggestions to improve the
service:

-   On the OVHcloud [AI community
    forum](https://community.ovh.com/c/platform/ai-ml)