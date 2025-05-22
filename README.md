# netdata-monitorin# Netdata Monitoring - Task 7
# Objective
Monitor system resources using Netdata and visualize real-time metrics.

# Steps
Installed Docker
Pulled and ran Netdata Docker container:
docker run -d --name=netdata -p 19999:19999 --cap-add=SYS_PTRACE --security-opt apparmor=unconfined netdata/netdata

Opened Netdata at http://localhost:19999
