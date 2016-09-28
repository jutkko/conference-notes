# Keynotes
## SAP, SIEMENS & Atos
Everyone trying to do agile innovation on cloudfoundry

## Women in Olympics Ursula, Atos
We start with a nice video. Atos partnered with the Rio Olympics.
Atos with Olympics since 1992. Rio Olympics had some of the non-critical Apps
from the cloud. PyeongChang Winter Games will be on cloud 100%. 40% of the
senior management from Atos Olympics team are women. Some key points

- Gender diverse companies are 15% more likely to outperform their peers

- Unconscious bias towards people who are similar to us, this is not good

## Pivotal cloudfoundry in Dutch Government
Nice intro movie. The Dutch seem to be having a better time than the British,
since they are paying more. Lol. Two-pizza team.

The Dutch Government is going to share their model. Where to find?

## The perfect cloudfoundry engineer?
Altoros work with 8 different IAAS

Candidates for a cloudfoundry job

- IAAS
= CI/CD
- 12 Factor apps
- Versioning, source code
- Networking
...

And some soft skills

- Dedicate time to self-education
- Team player
- Correct mindset

# Track Talks
## Highly Available cloudfoundry Deployment, Allstate
Manually install physical servers with VMware, with the "built-in" AZs

How is state shared? External databases. Planning to use Redis and RabbitMQ and
integrate into the existing AZs. Then will be forced to open up connections
between the AZs.

Implement in-house way to do zero-down time deployment. cloudfoundry part is
easy, statefull parts are hard.

## Google Cloud Platform, Eric and Colleen
Terraform script to set up the IAAS. Mentions concourse. Google Services out to
compare with the AWS one. They got a machine learning API.

Competition is on! Right now there is no RabbitMQ from Google.

## Local testing of containerized distributed systems, Justin Carter, S&W
Delmo is a tool that tests distributed systems

Use docker-compose, define the tests and delmo! Pretty cool! Justin uses
tmux!

## Windows Containers, HPE
Windows Server 2016 brings actual containers. Ability to bring Windows as a
first class citizen in cloudfoundry. Windows Cells GA soon?

SSH support.

Note that the guys are from HPE talking about Windows 2016 in cloudfoundry.
This is pretty cool.

How to try it out? Windows Server 2016 is not free?
Claims that shi is open source but not yet:
https://github.com/hpcloud/garden-hcs

## Undo for service brokers
Do a backup with an external plugin! If you want to explain the control flow of
your algorithm, use webcontrolflow diagram!

How to backup quickly? Continuous archiving. Not daily.

One final message from Dr Nic, getting something into cf cli is hard, therefore
people do sneaky workarounds!
