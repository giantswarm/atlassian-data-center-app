[![CircleCI](https://dl.circleci.com/status-badge/img/gh/giantswarm/atlassian-data-center-app/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/giantswarm/atlassian-data-center-app/tree/master)

# atlassian-data-center chart

Giant Swarm offers a atlassian-data-center App which can be installed in workload clusters.
Here we define the atlassian-data-center chart with its templates and default configuration.

**What is this app?**

This project contains Helm charts for installing Atlassian's [Jira Data Center](https://www.atlassian.com/enterprise/data-center/jira), [Confluence Data Center](https://www.atlassian.com/enterprise/data-center/confluence), and [Bitbucket Data Center](https://www.atlassian.com/enterprise/data-center/bitbucket) on Kubernetes.

**Why did we add it?**

We added this application to help our customers install JIRA on their workload clusters.

**Who can use it?**

Every customer interested in using Jira, Confluence or Bitbucket.

## Installing

There are 3 ways to install this app onto a workload cluster.

1. [Using our web interface](https://docs.giantswarm.io/ui-api/web/app-platform/#installing-an-app)
2. [Using our API](https://docs.giantswarm.io/api/#operation/createClusterAppV5)
3. Directly creating the [App custom resource](https://docs.giantswarm.io/ui-api/management-api/crd/apps.application.giantswarm.io/) on the management cluster.

## Requirements

Kubernetes: `>=1.19.x-0`

## Credit

* https://atlassian-labs.github.io/data-center-helm-charts/
