Overview
--------

The files contained in this repository focus on building out the Hyperledger Fabric environment on Linux on z Systems.

The build script installs and configures a Hyperledger Fabric environment on a Linux on
IBM z Systems instance.  The execution of this script assumes that you are starting
from a new Linux on z Systems instance.  The script will autodetect the Linux
distribution (currently RHEL, SLES, and Ubuntu) as well as the z Systems machine
type, and build out the necessary components.  After running this script, logout and
then login to pick up updates to Hyperledger Fabric specific environment variables.

The following components are installed:
- Docker and supporting Hyperledger Fabric Docker images
- Golang
- IBM Java 1.8
- Nodejs 6.9.5
- Hyperledger Fabric v1.0 core components
