# Switch Configurations

This folder contains the Cisco IOS configurations
for the two switches used in the VLAN configuration lab.

The configurations cover VLAN creation, access port
assignment, and trunk configuration between switches.

## Configuration Files

| Device | Description | Configuration |
|--------|-------------|---------------|
| SW1 | Office A Switch | [View Configuration](OFFICE_A_SW.txt) |
| SW2 | Office B Switch | [View Configuration](OFFICE_B_SW.txt) |

## Configuration Objectives

- Create VLANs 10, 20, and 30.
- Assign access ports to their respective VLANs.
- Configure an 802.1Q trunk between SW1 and SW2.
- Allow the required VLANs through the trunk link.

## VLAN Assignment

| VLAN ID | Department |
|---------|------------|
| 10 | Sales |
| 20 | IT |
| 30 | HR |

[Back to Lab Overview](../README.md)
