---
# Name of the event, <= 60 characters
title: From Zero to Production in Kubernetes
meta_desc: We’ll explore how to leverage the power of Python with Pulumi, an infrastructure as code platform to define and manage your Kubernetes deployments.
meta_image:

# A featured webinar will display first in the list.
featured: false

# Webinars with unlisted as true will not be shown on the webinar list
unlisted: false

# Gated webinars will have a registration form and the user will need
# to fill out the form before viewing.
gated: true

# The layout of the landing page.
type: webinars

# External webinars will link to an external page instead of a webinar
# landing/registration page. If the webinar is external you will need
# set the 'block_external_search_index' flag to true so Google does not index
# the webinar page created.
external: false
block_external_search_index: false

# The url slug for the webinar landing page. If this is an external
# webinar, use the external URL as the value here.
url_slug: from-zero-to-production-in-kubernetes

# Content for the left hand side section of the page.
main:
    # Webinar title.
    title: From Zero to Production in Kubernetes

    event_type: workshop # workshop | event

    # URL for embedding a URL for ungated webinars.
    youtube_url: #https://www.youtube.com/embed/l8Ha60IJ6m8?si=AiKU_4MK3w3aAE_l?rel=0

    # Sortable date. The datetime Hugo will use to sort the webinars in date order.
    sortable_date: 2024-07-25T09:00:00-07:00

    # Duration of the webinar.
    duration: 90 minutes

    # "virtual" will be shown under "show virtual events only", otherwise shown as City, State (seattle, wa)
    location: virtual

    # Description of the webinar.
    description: |
        Setting up your production Kubernetes environment brings many benefits including scalability and portability for your applications. Before you reach production, It’s important to understand key Kubernetes concepts and architectures available to keep your clusters secure and scalable. Ingress controllers are vital parts of any Kubernetes platform and NGINX ingress controller provides the best-in-class traffic management solution for cloud native apps and containerized environments.

        It’s important to use repeatable mechanisms to handle your ingress objects and controller deployments. Adopting infrastructure as code provides a mechanism to easily deploy production-ready applications in a repeatable manner. In this livestream, we’ll explore how to leverage the power of Python with Pulumi, an infrastructure as code platform to define and manage your Kubernetes deployments and build powerful abstractions that make getting to production easier than ever before.

    learn:
        - How to stand up Kubernetes including Amazon VPC, Amazon EKS, and other dependencies.
        - Setting up your ingress controller.
        - Deploying an app into your cluster.

    # The webinar presenters
    presenters:
        - name: Engin Diri
          role: Customer Experience Architect, Pulumi
          photo: /images/team/engin-diri.jpg
        - name: Damian Curry
          role: Business Development Technical Director, F5/NGINX

    # case-sensitive
    tags:
        level: Intermediate # Beginner, Intermediate, Advanced
        topics: ["NGINX", "Kubernetes"]
        languages: ["Python"]
        clouds: ["AWS"]

# The right hand side form section.
form:
    # HubSpot form id.
    hubspot_form_id: d448f8b6-c1a8-420d-8f9f-9975507e6d1e
    salesforce_campaign_id: 701PQ00000FCwsQYAT
---
