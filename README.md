# Packetbeat and Kibana Demonstration

## Overview
TODO: Write the overview

## Configure Notes
|Configuration|Notes|
|:------------|:----|
|network_mode |Configures the container to use the host network, allowing Packetbeat to capture network traffic on the host system.|
|environment  |Sets the environment variable BEAT_STRICT_PERMS to false. This is done to avoid permission issues when running Packetbeat as a container.|