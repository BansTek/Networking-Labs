# Switch Configurations

This folder contains the Cisco IOS configurations
for both switches used in the EtherChannel lab.

SW1 is configured in LACP active mode, while SW2
is configured in passive mode. Both switches use
Port-Channel 1 as a trunk to carry VLAN traffic.

## Configuration Files

| Device | LACP Mode | Configuration |
|---|---|---|
| SW1 | Active | [OFFICE_A-SW.txt](OFFICE_A_SW.txt) |
| SW2 | Passive | [OFFICE_B_SW.txt](OFFICE_B_SW.txt) |

## Configuration Scope

- LACP configuration
- Channel group assignment
- Port-Channel configuration
- Trunk configuration
- Allowed VLANs

[Back to Lab Overview](../README.md)
