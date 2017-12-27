# Prerequisites

## Oracle Cloud

This tutorial leverages the [Oracle Cloud](https://cloud.oracle.com/) to streamline provisioning of the compute infrastructure required to bootstrap a Kubernetes cluster from the ground up. [Sign up](https://cloud.oracle.com/en_US/tryit) for free credits.

[Estimated cost](???) to run this tutorial: $0.?? per hour ($?.?? per day).

> The compute resources required for this tutorial exceed the Google Cloud Platform free tier.

## Oracle Cloud Command Line Client

### Install the Oracle Cloud CLI

Follow the [documentation](https://docs.us-phoenix-1.oraclecloud.com/Content/API/SDKDocs/cliinstall.htm) to install the `oci` command line utility.

Ensure that the client is installed and working:

```
oci -v
```

### Configure the CLI 

Follow the [documentation](https://docs.us-phoenix-1.oraclecloud.com/Content/API/SDKDocs/cliconfigure.htm) to configure the `oci` command line utility.

To setup a default ID and compute region:

```
oci setup config
```

Next: [Installing the Client Tools](02-client-tools.md)
