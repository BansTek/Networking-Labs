# Network Verification

This folder contains the verification commands and
connectivity tests for the VLAN configuration lab.

The purpose of these tests is to check whether the VLANs,
access ports, and trunk links are configured correctly.

## Verification Commands

| Command | Purpose |
|---------|---------|
| show vlan brief | Verify VLANs and port assignments |
| show interfaces trunk | Verify trunk status and allowed VLANs |
| show interfaces status | Check switch port status |
| show mac address-table | Check learned MAC addresses |

## VLAN Verification

![VLAN Verification](VLAN_OFFICE_A_brief.png)

![VLAN Verification](VLAN_OFFICE_B_brief.png)

## Trunk Verification

![Trunk Verification](TRUNK_OFFICE_A_status.png)

![Trunk Verification](TRUNK_OFFICE_A_status.png)

## Connectivity Testing

| Source | Destination | Expected Result | Actual Result |
|--------|-------------|-----------------|---------------|
| SALES-1 | SALES-2 | Successful | Successful |
| IT-1 | IT-2 | Successful | Successful |
| HR-1 | HR-2 | Successful | Successful |
| SALES-1 | IT-1 | Failed | Failed |
| HR-1 | SALES-2 | Failed | Failed |

## Same-VLAN Connectivity

![Successful Ping](PC_1_PC_4_ping.png)

## Inter-VLAN Isolation

![Inter-VLAN Isolation](NO_interVLAN-Routing.png)

Devices belonging to different VLANs are not expected
to communicate because inter-VLAN routing is not
configured in this lab.

[Back to Lab Overview](../README.md)
