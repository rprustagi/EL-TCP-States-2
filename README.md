# EL-TCP-States-2
In this we describe practical conditions which can lead each of specific state in TCP tear down phase.

To enable an better understanding 6 experiments have been described along with required firewall conditions and required program to witness even the transient states such as FIN_WAIT1, FIN_WAIT2, LAST_ACK etc. While in general, nc (netcat) has been used as the applications on both sides, but in some cases where timing of packets is important and needs to be coordinated, a specific program *tcp_client.py* has been used which is available as part of this repoistory.
