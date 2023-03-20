+++
title = "RHCSA"
weight = 3
description = '''
'''
+++
## Summary

## Pre-requisites

## Experiences

### Gabe Stone
Hey everybody!

As some of you may know, I recently earned my [Red Hat Certified System Administrator (RHCSA)](https://www.redhat.com/en/services/training/ex200-red-hat-certified-system-administrator-rhcsa-exam) certification! If you want to eventually earn your Red Hat Certified Engineer (RHCE) certification, you need to have a current RHCSA certification.

The 2.5 hour exam was certainly not easy; don't think you'll coast on your years of Linux knowledge to pass ;) Yes, you'll be dealing with things like NTP, user management & permissions, but you'll also be dealing with logical volumes, the RHEL container stack, and probably most important: resetting root credentials when you have been locked out of a RHEL system.

So here are some tips, suggestions and warnings (with the caveat that YMMV based on the exam environment/domain you get):

1. One thing you will almost absolutely  **NEED**  to do on the exam is reset root's password on a RHEL VM so you can get back into the system and perform a set of tasks. For me, this task was the first task in one of two exam sections. If you can't complete this task, then you will be unable to perform the following tasks in that section, getting effectively a zero on that section. It happened to me on my first of two attempts, resulting in an ultimate "no pass" for me.

2. Know:

a. the CRI-O based container stack for RHEL: podman for sure (skopeo & buildah to a lesser degree probably; you'll need to create images, containers, and start rootless containers as a service)

b. setuid, setgid and sticky permissions in addition to regular ones (that said, I didn't have to deal with ACL's although it may be good to review those)

c. find files on a system given a parameter or two (i.e. all files owned by a specific user)

d. SELinux (i.e. change security context on files and ports to allow a web server to serve them)

e. how to create & resize physical volumes, volume groups and logical volumes (most of the utilities you'll need are prefixed with pv, vg & lv with a pretty consistent command nomenclature)

f. set up a cron job (better know each of those fields in order; I used an acronym: "My horse died, my dear")

g. mount NFS locations on boot (know that exports file!)

h. add default yum repos given a base URL

3. Some questions will require you to perform tasks as a specific user. Read the whole question - don't assume all exam tasks are done as root!

4. You will be consoling in to two VM's for your work during the exam. They will not have any Internet access, so don't expect to be able to search for answers, although you will have access to man pages (remember those?).

5. You will need an  _external_  webcam that allows full view of your work area. Your built-in laptop camera won't cut it.

6. Don't spend too much time in man pages & budget your time wisely given the time remaining and tasks that you have left to do.

7. This is more of a personal anecdote, but don't think to yourself "I'll study then sign up for the exam". Life happens and your study periods will be more sparse which means you'll retain less. Sign up for the exam FIRST, which gives you a goal post and will maximize study retention in the intervening time.

8. Everyone learns differently, but I used two books and local practice VM's to study up (one book was essentially my tutorial, the other a reference; contact me if you'd like to know what I used). There are also very effective Red Hat trainings that hew very closely to exam objectives (contact   for details).

Lastly, don't get discouraged if you don't pass the first time. It happened to me, so I adapted my learning approach, reviewed weak topics and signed up for a retake that same day. It's a good certificate to get, if only to prove & harden your knowledge, much of which many of us absorbed by experience.

Best of luck to you on the RHCSA exam, and please comment here or hit me up in Slack with any questions!



*****

[[category.storage-team]] 
[[category.confluence]] 
