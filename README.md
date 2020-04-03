# SNMP

Data Tracker
https://tools.ietf.org/html/rfc1155

# Aim

it aims at collecting statics for mgmeted host, and make config for secuirty issues or just the monoitor features. see RFC 1155 & 3411 ~ 3414

# CLI 

get

set 

trap

# Infra

      mgmt devices (agent resides on software called NMS) ------agent communicates with server-------- mgmt server (manager) to collect info
      
# Data Transfer

it uses PDUs, protocol data units.

# Constraints

The character of indescriminate(不加以選擇) may cause an adverse effect on Network Performance. 

It consumes the bandwidth(due to timeless notify and report), CPU(due to formatting), and Memory resources on the target network devices.  
