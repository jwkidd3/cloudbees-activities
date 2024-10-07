name: rollout-control-title
class: title, shelf, no-footer, fullbleed
background-image: linear-gradient(135deg,#279be0,#036eb4)
count: false

# CloudBees Feature Management<br>Controlling the Value of a Feature Flag

---
name: rollout-control-overview
# Controlling the Value of a Feature Flag

In order to control the value of a feature flag with CloudBees Feature Management for this lab, we will be creating an experiment in the dashboard.
<br/>
<br/>
An experiment in the CloudBees Feature Management dashboard refers to the definition of a ruleset around a specific feature flag. It is within the experiment that we will decide if a flag should be on or off, for which users, what percentage of users, etc. Any rule that applies to a feature flag will be defined inside of an experiment.

---
name: rollout-control-override

# Introduction to Flags Override View

The *Flags Override view* is useful for debugging purposes. It allows developers to expose a view that shows the current status for each flag, and it allows the user to override these flags. This view is usually exposed to only developers, the QA team, and the product team.
<br/>
<br/>

.img-right[
![:scale 75%](img/rox_overrides.png)
]

.img-left[
In the *Flags Override view*, a flag can appear in the following states:
* The *flag is on* state means the value from the server of a flag is on and is not overridden on the device.
* The *flag is off* state means the value from the server of a flag is off and isn’t overridden on the device.
* The *flag is overridden* state means the value from the server is overridden on this specific device.
]


---
name: rollout-control-lab
# Lab - Controlling the Value of a Feature Flag

* In this lab you will control the value of a flag by creating an experiment via the CloudBees Feature Management dashboard.
* For local testing or development, we will need to specify values for each flags on our local machines. In order to do this without affecting others' work, we will implement the Flag Override and toggle the values as needed.
* The *Controlling the Value of a Feature Flag* lab instructions are available at:
  * https://cloudbees-feature-flags.labs.cb-sa.io/labs/experiment/ 

---
name: rollout-control-review

# Controlling the Value of a Feature Flag Lab Review

Experiments are an important concept in CloudBees Feature Management. With this lab complete, you can now control the value of "default.sidebar" and "default.title" by creating experiments via the CloudBees Feature Management dashboard.
<br/>
<br/>
You also used the *Flags Override view* UI element to modify flag values to allow for validation on your local machine without affecting others' work.
