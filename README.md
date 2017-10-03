# bridge_workshop_aws_iot_cloud
Bridge workshop connecting AWS IoT with mbed Cloud

Logs:

    10/3/2017: Initial checkin of v2.2 workshop content release

Links for the workshop

- Amazon AWS Management Console:
      https://aws.amazon.com/console/

- Amazon HowTo: Creating your AWS secret key and ID:
      http://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSGettingStartedGuide/AWSCredentials.html

- Windows USB Driver for mbed:
      https://os.mbed.com/media/downloads/drivers/mbedWinSerial_16466.exe

- Windows Putty Serial Terminal:
      http://www.putty.org/

- Docker Toolbox for Windows 7:
      https://github.com/docker/toolbox/releases/tag/v1.12.2

- Docker Engine for Mac (do not install the "Toolbox" version on the mac):
      https://docs.docker.com/engine/installation/mac/

- Docker Engine for Linux:
      https://docs.docker.com/engine/installation/linux/ 

- Mac Serial Terminal 
      http://freeware.the-meiers.org/CoolTerm_Mac.zip

- Mac "git"
      https://git-scm.com/download/mac

- Linux Serial Terminal 
      http://freeware.the-meiers.org/CoolTerm_Linux.zip

- mbed Developer IDE:
      https://os.mbed.com

- mbed Cloud Dashboard:
      https://portal.mbedcloud.com

- K64F Sample Project used in Workshop:
      https://github.com/ARMmbed/mbed-cloud-sample/

- Bridge Configuration Panel (local)
      https://192.168.99.100:8234

"Git" command used to import the bridge container installer:

      git clone https://github.com/ARMmbed/connector-bridge-container-installer

JSON sample used as command to send to device:

      {"path":"/311/0/5850", "ep":"ENDPOINT_NAME_GOES_HERE", "new_value":"0","coap_verb":"put"}
