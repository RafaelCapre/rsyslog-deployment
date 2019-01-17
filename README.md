# rsyslog-deployment

I had to create a rsyslog server on top of the kubernetes, so I configured a configmap and a pvc to store the logs, in which I shared the PVC with Splunk to direct the logs that are in my cluster in the cloud. As I had some complications in doing of the zero, I decided to share not to go through the same headache :)

ps: Because of my laziness, service and configmap are in deployment.

ps2: PVC was created based on the IBMCLOUD disk configurations.
