# Getting Started with TestProject
## Install Agent
- create account at [TestProject](https://testproject.io/)
- Agents > Linux

## Configure permission
- `cd` into the agent.sh directory
- `chmod +x ./TestProject_Agent_3.5.0.sh`

## Start Agent
- `./TestProject_Agent_3.5.0.sh`

## Permanently add TestProject into env 
- vim bashrc
- get path of the Agent script (`/home/keoy/testproject/agent/bin/`)

## Start Agent
- cd into ^ (`cd /home/keoy/testproject/agent/bin/`)
- `./testproject-agent-app` //run this file from ./ directory
OR
- `testproject-agent-app` //will run if added in bashrc

## Automated Testing
- open emulater on Android Studio OR connect to physical device via data cable
- device should be detected on TestProject

