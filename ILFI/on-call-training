Scenario Name: 📟On-Call Training
Description: People all over the world are relying on us to keep the lights on 💡 for their internet services. Use this Scenario to train engineers to be on-call.  \n\n1. Can your on-call engineers identify that a host was shutdown? How? What tools do they need access to?  How long did it take for the host to shutdown? \n4. How long did it take for it to recover? \n5. Did they get notified in any way? Were they able to see this occur in the monitoring/logs? Did they know what steps they should do next?
Hypothesis: When this scenario runs it will result in a host shutting down. Use this scenario as the first step of your on-call training program.

------------------------
Scenario Steps

Step count: 1
Delay: 5

Attacks
------------------------

Attack 1
------------------------

AttackType: ILFI

ImpactDefinition:
CommandType: Shutdown
commandArgs:
  reboot: true
  delay: 1
  length: 0

TargetDefinition:
targetType: Host
Strategy
Count: 1
StrategyType: Random

