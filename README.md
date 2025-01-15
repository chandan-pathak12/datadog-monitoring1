Aim:- Learning datadog with any basic example

Pre-requisites:- datadog login and then

1. Create an IAM policy with detail given in policy.txt , paste it in json
2. create an IAM role and associate it with the above policy. Please select trusted entity "AWS account" with below
![Alt Text](/aws-IAM.png)
and then use detail available in datadog document.
3. If you ever want to stop the Datadog Agent, run:

      sudo systemctl stop datadog-agent

  And to run it again run:

      sudo systemctl start datadog-agent

