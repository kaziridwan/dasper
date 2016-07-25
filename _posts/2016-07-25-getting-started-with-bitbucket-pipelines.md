---
published: false
tags:
  - hypekiller
  - bitbucket
  - pipelines
layout: article
---
# Getting started with Bitbucket Pipelines

With introduction of [Docker](https://www.docker.com/what-docker), the development of new breed of CI systems was inevitable. And now the hype is on with repository hosting platforms releasing their build in CI (Continuous Integration) system, starting with bitbucket releasing their [pipelines](https://bitbucket.org/product/features/pipelines) and Gitlab releasing their own version of [pipelines](https://about.gitlab.com/2016/05/22/gitlab-8-8-released/) in response.

<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/p5KgjeZB8Ww?rel=0&amp;controls=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

It runs your builds with Docker. If you don't specify an image, it'll run your build with the default one, but it's better to get an environment that meets the specific needs of your configuration.
There are always two main pipelines: default and branches.

# Prerequisites

By now you have realized that you need to have some idea about Docker, but it might be not that much important either, cause we'll try to use as less Docker as possible here.

You might also try considering reading this article about [continuous delivery pipelines](http://devops.com/2014/07/29/continuous-delivery-pipeline/)

## Instructions

The steps are simple, and can be found [in the official doc](https://confluence.atlassian.com/bitbucket/get-started-with-bitbucket-pipelines-792298921.html#GetstartedwithBitbucketPipelines-Step1:InstallBitbucketPipelines)

1.	Signup and install Bitbucket Pipelines
2.  Enable Bitbucket Pipelines
3.  Configure your building environment

## Get the hands dirty

### 1.Configure bitbucket-pipelines.yml

You can find official page [here](https://confluence.atlassian.com/bitbucket/configure-bitbucket-pipelines-yml-792298910.html)
