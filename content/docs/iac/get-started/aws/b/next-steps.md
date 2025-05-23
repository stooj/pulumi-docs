---
title_tag: Next Steps | AWS
title: Next steps
h1: Next Steps with Pulumi & AWS
stepper_link: "Congratulations!"
meta_desc: This page provides a list of tutorials that take a deeper dive into
            AWS cloud resources.
weight: 9
menu:
    iac:
        name: Next steps
        parent: aws-b-get-started
        weight: 9

aliases:
- /docs/iac/get-started/aws/b/next-steps/
---

Congratulations! You've successfully provisioned some cloud resources using Pulumi. By completing this guide you have successfully:

- Created a Pulumi new project.
- Provisioned a new S3 bucket.
- Turned it into a static website.
- Created a website component for easy reuse.
- Destroyed all of the resources you've provisioned.

Below are some recommended next steps, including examples and tutorials that you can explore or use them as a foundation for your own applications and infrastructure projects. Also be sure to [join the Community Slack](https://slack.pulumi.com/) to meet fellow IaC practitioners.

## Try Pulumi ESC (Environments, Secrets, and Configuration)

[Pulumi ESC](/docs/esc/) is a centralized secrets management and orchestration service. It introduces the concepts of _environments_ --- managed collections of static and dynamic settings that you can use to configure any project, stack, application, or service, including with short-lived cloud credentials through OpenID Connect.

With Pulumi ESC you can:

- **Stop secret sprawl.** Pull and sync configuration and secrets with any secrets store – including HashiCorp Vault, AWS Secrets Manager, Azure Key Vault, GCP Secret Manager, 1Password, and more – and consume in any application, tool, or CI/CD platform.
- **Trust (and prove) your secrets are secure.** Every environment can be locked down with role-based access controls (RBAC) and versioned with all changes fully logged for auditing.
- **Ditch `.env` files.** No more storing secrets in plaintext on dev computers. Developers can easily access secrets via CLI, API, Kubernetes operator, the Pulumi Cloud UI, and in-code with Typescript/Javascript, Python, and Go SDKs.

{{< get-started-next-step path="/docs/esc/get-started/" label="Learn more about Pulumi ESC" ref="gs-aws-esc" >}}

## Try a tutorial

Let our AWS tutorials guide you through key Pulumi concepts.

{{< get-started-next-step path="/docs/using-pulumi/" label="Browse tutorials" ref="gs-aws-tutorials" >}}

## Launch a new project with a template

Easily deploy the most common cloud architectures, from [static websites](/templates/static-website/aws/) to [serverless applications](/templates/serverless-application/aws/), [virtual machines](/templates/virtual-machine/aws/), [container services](/templates/container-service/aws/), and [Kubernetes clusters](/templates/kubernetes/aws/).

{{< get-started-next-step path="/templates/" label="Browse templates" ref="gs-aws-guides" >}}

## Dive into the docs

Read more about Pulumi's architecture and foundational concepts in depth, including [projects](/docs/concepts/projects/), [stacks](/docs/concepts/stack/), [configuration](/docs/concepts/config/), [secrets](/docs/concepts/secrets/), [resources](/docs/concepts/resources/), [state](/docs/concepts/state/), and more.

{{< get-started-next-step path="/docs/concepts/" label="Read the docs" ref="gs-aws-docs" >}}

## Check out the blog

Browse the latest posts on using Pulumi with AWS, including everything from new AWS products and features to technical architectures and best practices.

{{< get-started-next-step path="/blog/tag/aws" label="Browse AWS posts" ref="gs-aws-blog" >}}
