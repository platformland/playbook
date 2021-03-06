# Measuring and monitoring

The primary users of a platform tend not to be the public themselves, but rather the people who use them to create services for the public (be it civil servants, charities or private sector companies). Ultimately, the success of a platform will be perceived by the success of those services, not the platform itself. This means platform teams need to understand what they need to measure to operate the platform, and what data their users need to provide great services to the public.

## 1. Understand what data your team needs

A team developing a platform will have clear a set of needs that relate to the operation and improvement of that platform. These may include some of the following:

* Are people self-serving? (For example, what's the ratio of meetings to users?)
* Are people using the documentation?
* What code libraries are being used?
* Where are the users (central government, local government, private sector?)
* How many distinct services and organizations are using the platform?
* What is the service up-time? (Up-time targets will likely vary depending on the type of platform).

Conduct user research with your team and understand what data they need to do their job effectively.

## 2. Understand what data your users need

Because platforms are component parts of services, the success of a platform will ultimately be perceived by the success of those services. As such, it is critical to understand what data your users will need access to as part of the operation of their service. Google, for example, maintains specific tools to help Android developers understand app performance.[^1]

Much of the data users need may be domain specific, so conduct user research with them to understand their needs.

## 3. Use a "show back" approach to build common understanding of cost and efficiency

The ideal is that platforms are funded centrally are operated for free to create the broadest possible public good. However, it is still important that your users understand the cost and wider value of running each platform. This approach is called "show back" (as opposed to "pay back" where users are charged for use).

If it is not possible to show back actual monetary costs, start with the percentage of use represented by different users (for example the number of API calls or transactions). The aim is to create a shared mindset of ownership and an understanding of cost.[^2]

Use a "show back" approach to create a shared understanding of efficiency and cost among your users. Where possible, measure cost-per-use and be transparent to users of the platform, even if they are using the platform for free.

## 4. Publish performance data in the open

Publishing performance data can help users better understand what a platform does and how it is being iterated.

Italy's Team per la Trasformazione Digitale publish data about the rollout of the National Resident Population Register, including register size and the number of municipalities that have migrated to it.[^3] India's Aadhaar and Estonia's X-road also have public dashboards that show usage, while the UK's GOV.UK Pay publishes data about the organizations using it and the total value of the payments that it has processed. [^4][^5][^6]

Publish performance data about your platform in the open.

## 5. Prepare for unexpected user behaviour

It is in the nature of a platform that you don't know exactly how or when people will use it. If someone is going to do something new with your platform, they will likely not tell you in advance. This is especially true if you have designed for self-service. 

Understand the roadmaps of any large services making use of your platform so you can better anticipate their usage. Use analytics to understand emerging use-cases of the platform.

## 6. Create a public system status page

It is standard practice for commercial platforms to maintain a status page that details the current status of the system.[^7] Many digital service units are following this practice with the UK, Australia and US (among others) maintaining status pages for their platforms.[^8] [^9] [^10]

It is also standard practice for commercial platforms to publish public incident reports detailing any outages or security issues. [^11]

Create a public status page for each platform and ensure users can find it. Once resolved, publish incident reports detailing outages or security issues.

## 7. Use the privileged position of the platform respectfully

Because platforms centralize, the teams operating them have the power to see how it is being used for a range of different users. This can be used to identify usage patterns that can be generalized into new features, or used to improve how others use the platform. However, with great power comes great responsibility. Understand the ethical and privacy implications of any new data analysis or collection.

> ## Example: Monitoring and tooling for Android
> 
> "Google maintains specific tools to help Android developers understand app performance and respond to issues."
> 
> "The dynamic is that whatever you do with your platform, you are perceived through the lens of the applications that run on it, so you need to provide tooling as well as APIs."
> 
> "We have a tonne of reporting that's built into the platform. If an application crashes, the system shows a dialogue: "Send report?" --- with user permission, it'll send back anonymized (non-personally identifiable) system information to the core team (so we can debug our platform) and it'll send it to the app developers so they are aware of issues. A bunch of energy is invested in Play Developer Console where we give developers a tonne of metrics & tools to help them improve their applications."
> 
> — Dr Adam Connors, Senior Google Engineering Manager
{:.box}

[^1]:   Google, "Google Play Console", [https://developer.android.com/distribute/console](https://developer.android.com/distribute/console). Retrieved 9th June 2019.

[^2]:   This white paper from Amazon explains how to use measurement and transparency to create a shared understanding of cost and efficacy. Amazon, "Creating a Culture of Cost Transparency and Accountability", March 2018, [https://docs.aws.amazon.com/whitepapers/latest/cost-optimization-transparency-accountability/introduction.html](https://docs.aws.amazon.com/whitepapers/latest/cost-optimization-transparency-accountability/introduction.html)

[^3]:   Team Digitale, "National Resident Population Register (ANPR) - Digital Transformation Team", [https://teamdigitale.governo.it/en/projects/anpr.htm](https://teamdigitale.governo.it/en/projects/anpr.htm). Retrieved 9th June 2019.

[^4]:   UIAI, "Aadhaar Dashboard", [https://uidai.gov.in/aadhaar\_dashboard/](https://uidai.gov.in/aadhaar_dashboard/). Retrieved 9th June 2019.

[^5]:   "X-TEE", [https://www.x-tee.ee/factsheets/EE/#eng](https://www.x-tee.ee/factsheets/EE/#eng). Retrieved 9th June 2019.

[^6]:   HM Government, "Dashboard, GOV.UK Pay,  GOV.UK", [https://www.gov.uk/performance/govuk-pay](https://www.gov.uk/performance/govuk-pay). Retrieved 9th June 2019.

[^7]:   For examples see: [https://status.twilio.com](https://status.twilio.com), [https://www.gocardless-status.com](https://www.gocardless-status.com), [https://status.aws.amazon.com](https://status.aws.amazon.com) and [https://status.stripe.com](https://status.stripe.com)

[^8]:   "GOV.UK Pay Status", [https://payments.statuspage.io](https://payments.statuspage.io). Retrieved 9th June 2019.

[^9]:   "cloud.gov.au Status", [https://status.cloud.gov.au](https://status.cloud.gov.au). Retrieved 9th June 2019.

[^10]:  "cloud.gov Status", [https://cloudgov.statuspage.io](https://cloudgov.statuspage.io). Retrieved 9th June 2019.

[^11]:  See [https://aws.amazon.com/message/41926/](https://aws.amazon.com/message/41926/) and [https://gocardless.com/blog/incident-review-api-and-dashboard-outage-on-10th-october/](https://gocardless.com/blog/incident-review-api-and-dashboard-outage-on-10th-october/) for examples "
