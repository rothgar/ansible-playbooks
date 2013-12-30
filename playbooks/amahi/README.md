Amahi playbook
=============

This playbook will attempt to get an [Amahi](http://amahi.org) 7.1 headless installation to IMO a more usable place. One of the main things it does is installs and configures greyhole for storage pooling but it will also install VMware tools if you are running the installation from VMware (or ESXi) and it will configure postfix.

Not all of the setup works yet, and some of it will go away with Amahi 7.2. But I wanted to make my test installs repeatable.

## ToDo ##
[ ] Finish VMware tools installation

[ ] Finish postfix setup for Gmail SMTP

[ ] Configure greyhole instead of just installing it

[ ] Create users

[ ] Create shares

[ ] Install available apps
