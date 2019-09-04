# uptm-io-docs

## Links

Uptm.io website [https://uptm.io](https://uptm.io?utm_source=docs)

Wirnexteam public github repos [https://github.com/wirnexteam](https://github.com/wirnexteam)

## What is Uptm.io

Uptm (short for Uptime) &mdash; is a platform for web developers and website owners. There are two core features (and more to come) such as [***Website Monitoring***](#website-monitoring) and [**Automated Builds**](#continuous-integration) for Continuous Integration (CI).

## Website Monitoring

Everyone knows that any website can accidentally go down.
It might be caused by a web server or a code error or by any other reason.
It is always better when you as the website owner get notified about that sooner than your visitors.

[Uptm.io](https://uptm.io?utm_source=docs) is here to help you keep your websites up and running.

### How does it work
We monitor your website periodically and check if it is up or down and immediately notify you when an accident happens.

### What kind of resources can be monitored?
We can monitor any resources that might be seen by HTTP protocol. Also we support TCP monitors where you can send raw requests and analyze responses. See [Advanced Monitoring](/monitoring) for reference. 

### How to create a Monitor for my Website?

First you'll have to [create an account](https://login.uptm.io/signup?utm_source=docs) to let us know your email we will send the alerts to.
Then [Sign In](https://login.uptm.io/signin?utm_source=docs) and you'll see the **Dashboard**.

![Dashboard](/img/dashboard.png)


Navigate to **Monitors** and click **Add**.
You'll see a form with name, type, host and other fields.
In this example frequency _1 min_ means that we're going to check the website availability every minute (60 seconds). And _Down alert time_ is the minimum time a monitor should spend in Down state before we send you an alert.

![Create a Monitor](/img/monitoring/create-http-monitor.png)


Then click **Add** and you'll be navigated to the **Monitors** index where you can see the card of your just created monitor.

![Monitor](/img/monitor-card.png)

:heavy_check_mark:

On the Monitor details page you can also see events list and response time chart.

![Monitor Details](/img/monitor-details.png)

 
## Automated Builds for CI

### Demo Projects with CI config set up

#### NodeJs 
[https://github.com/wirnexteam/demo-ci-nodejs](https://github.com/wirnexteam/demo-ci-nodejs)
 
[https://github.com/wirnexteam/demo-ci-nodejs-dockerless](https://github.com/wirnexteam/demo-ci-nodejs-dockerless)

### Core Concepts of CI

### What is a builder

### Setting Up Builds for a Repository


