---
name: Bug report
about: Create a report to help us improve. Note that reports that are not bugs will generally not be accepted.
title: ''
labels: ''
assignees: ''
---

<!--
Thank you for using Kurento! If you are here it means you found a problem...
Please provide enough information so that others can review your report.

Check out the 4 steps on **how to get help**:
https://github.com/Kurento/.github/blob/master/SUPPORT.md

To write an Issue report, read our Reporting Guidelines:
https://doc-kurento.readthedocs.io/en/latest/user/support.html#reporting-issues
-->


## Prerequisites
<!--
Go over all the following points, and fill with an 'X' in all the boxes that apply.
If you're unsure about any of these, don't hesitate to ask. We're here to help!
-->

* [] I have read the SUPPORT document
  <!-- You can read it here:
  https://github.com/Kurento/.github/blob/master/SUPPORT.md
  -->

* [] I have checked the Troubleshooting Guide
  <!-- You can find it here:
  https://doc-kurento.readthedocs.io/en/latest/user/troubleshooting.html

  INSTALL DEBUG SYMBOLS if your report is about a CRASH in Kurento,
  before providing us with a stack trace:
  https://doc-kurento.readthedocs.io/en/latest/dev/dev_guide.html#install-debug-symbols
  -->

* [] I have tested with the latest version of Kurento
  <!-- You can check which one is the latest version here:
  https://doc-kurento.readthedocs.io/en/latest/project/relnotes/index.html
  -->


## Issue description
<!--
A clear and concise description of what the bug is.

If you paste code or logs, surround with ```triple backquotes``` to keep format.
-->


## Context
<!--
How has this issue affected you? What are you trying to accomplish?
Providing context helps us come up with a solution.
-->


## How to reproduce?
<!--
Explain the exact steps that other developer should follow in order to
reproduce the same issue.

For example:
1. Create this pipeline: "..."
2. Use these settings: "..."
3. Click "Start"
4. See error
-->


## Expected & current behavior
<!-- Tell us what should happen, and what happens instead. -->


## (Optional) Possible solution
<!--
Not obligatory, but suggest a fix/reason for the bug,
or ideas on how to implement the solution.
-->


### INFO about Kurento Media Server

* Kurento version:  <!-- E.g. 6.12.0, nightly -->
* Server OS:        <!-- E.g. Ubuntu 16.04 (Xenial), 18.04 (Bionic), etc. -->
* Installation method:
    <!-- Fill with an 'X' in all the boxes that apply. -->
  - [] apt-get
    <!-- https://doc-kurento.readthedocs.io/en/latest/user/installation.html#installation-local -->
  - [] Docker
    <!-- https://doc-kurento.readthedocs.io/en/latest/user/installation.html#installation-docker -->
  - [] AWS
    <!-- https://doc-kurento.readthedocs.io/en/latest/user/installation.html#installation-aws -->
  - [] Built from sources
    <!-- https://doc-kurento.readthedocs.io/en/latest/dev/dev_guide.html#dev-sources -->


### INFO about your Application Server

* Language:                 <!-- E.g. Java, Node.js, browser JavaScript, etc. -->
* Kurento Client version:   <!-- E.g. 6.12.0, nightly -->


### INFO about end-user clients

* Device(s):    <!-- E.g. PC, Mac, Android, iPhone, etc. -->
* OS(es):       <!-- E.g. Ubuntu 18.04, Windows 10, iOS 12, etc. -->
* Browser(s):   <!-- E.g. Firefox 74, Chrome 80, Safari 12.0, etc. -->


## INFO about your environment
<!--
Include as many relevant details about the environment where you experienced
the issue. Include things like:
* What Kurento Endpoints are used, and how are connected.
* If you are configuring STUN or TURN in Kurento and/or in the browsers.
* If the WebRTC streams are being relayed through your TURN servers.
* The network topology between servers / services / containers / etc.
* If there are any web proxies.

ANYTHING that you think might be relevant or useful.
-->


### Commands output
<!--
Paste output of running these commands in the same machine where
Kurento Media Server is running.

Surround with ```triple backquotes```, to keep the output correctly formatted.
-->

```
cat /etc/lsb-release

kurento-media-server --version

dpkg -l | grep -Pi 'kurento|kms-|gst.*1.5|nice'
```
