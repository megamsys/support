MegamVertice/VirtEngine Support
=================

This repository tracks [bugs and feature requests] (https://github.com/megamsys/support/issues?state=open) &  for MegamVertice's public cloud hosting made easy/private enterprise deployment platform.

Before opening a new Support Issue:
-----------------------------------

* Troubleshooting common issues:

  - Documented [FAQs](http://docs.megam.io/faq/).  
  - How to [Troubleshoot](http://docs.megam.io/troubleshooting/).  


Open a new Support Issue:
-------------------------

* Go to the [issues list] (https://github.com/megamsys/support/issues?state=open) and create a new issue by filling out the [New Issue Template](https://github.com/megamsys/support/issues/new).
* The following is needed to expedite the resolution of your issue:

    - Describe the issue with as many details as possible.
    - If your issue is regarding a **deployment**, it is essential to include:

        - Link to the failed deployment. We'll use the administrator id to impersonate and debug.
        - Any logs as per [troubleshooting](http://docs.megam.io/troubleshooting/)
        - Upload screenshots if there is an error reported in the userinteface.
    - Indicate if the issue is impacting your business and/or is blocking
* NOTE: the absence of the above information will delay the mitigation of the issue

Track Issue Status:
------------------

**We triage all new issues in 1 business day.** We will update the issue frequently with latest status, for you to be up to speed on the progress towards resolution.

NOTE: If you have an issue that is impacting your business and/or is blocking, please indicate it in your support issue. We will escalate and prioritize resolution.

Support Process:
----------------
During the triage, we tag the support issues per our Support Process flow.

**Process related labels:**

-  [investigate](https://github.com/megamsys/support/labels/investigate)/[implement](https://github.com/megamsys/support/labels/implement): The issue has gone through Shippable’s daily internal support triage and the next action towards resolution has been identified and initiated.
- [in progress](https://github.com/megamsys/support/labels/in%20progress): An engineer is actively working on resolving the issue.
- [need info from customer](https://github.com/megamsys/support/labels/need%20info%20from%20customer): Shippable requires additional information regarding the issue in order to continue troubleshooting the issue. The customer who opened the issue is accountable to provide this information, to make progress towards resolution.
- [resolved](https://github.com/megamsys/support/labels/resolved): The issue has been mitigated either through code changes deployed into production and/or the issue has been successfully addressed.
- [deferred](https://github.com/megamsys/support/labels/deferred): The resolution of this issue has been deferred for now and will not be actively worked on.

The issue will be closed if it meets one of the following conditions:

- The issue has been tagged **resolved**. Customers are welcome to re-open the issue if they feel their issues are not resolved.
- The issue has been tagged **need info from customer** and 3 business days have passed with no response from the customer.
- The issue has been tagged **duplicate** and has the link to the original issue being tracked.
- The issue has been tagged **deferred**.

The above process/tags are transparent, thereby enabling our customers who opened support issues to know the most current status of their issues.

**Issue related labels:**

- [bug](https://github.com/megamsys/support/labels/bug): Shippable has determined that the product is not behaving the way it is intended to. It requires a code change to resolve the issue.
- [feature request](https://github.com/megamsys/support/labels/feature%20request): Feature currently does not exist. If implemented, it is intended to provide additional value to our customers
- [update content](https://github.com/megamsys/support/labels/update%20content): Customer specifically wants to know how to use/implement a feature. Issues tagged as such, will be updated in one of our content platforms such as Documentation, Blogs, videos for customers to self-serve in the future.
- [technical issue](https://github.com/megamsys/support/labels/technical%20issue):  Customer is unable to use Shippable service per expectation & needs help to resolve the issue. Issues determined to be bugs & feature requests will not be tagged as technical issues.
- [question](https://github.com/megamsys/support/labels/question): All non-technical issues faced by customers. For e.g. billing questions.
- [duplicate](https://github.com/megamsys/support/labels/duplicate): This exact issue is already being tracked

There are other labels, not documented here, that MegamVertice/VirtEngine uses internally for classifying and assigning the support tickets.
