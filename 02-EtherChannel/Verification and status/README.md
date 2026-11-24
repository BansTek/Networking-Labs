# Network Verification

This section contains the verification results
for the EtherChannel lab. The tests are performed
to check whether both physical links are properly
bundled and whether connectivity is maintained
when one link fails.

## Verification Commands

| Command | Purpose |
|---|---|
| show etherchannel summary | Check EtherChannel status |
| show interfaces trunk | Verify trunk configuration |
| show lacp neighbor | Verify LACP neighbor |
| show interfaces port-channel 1 | Check logical interface |
| show spanning-tree | Verify STP status |

## EtherChannel Status

![EtherChannel Status](ETHERCHANNEL_OFFICE_A_summary.png)
![EtherChannel Status](ETHERCHANNEL_OFFICE_B_summary.png)

## Trunk Status

![Trunk Status](TRUNK_OFFICE_A_status.png)
![Trunk Status](TRUNK_OFFICE_B_status.png)

## Connectivity and Redundancy Testing

| Test | Expected Result | Actual Result |
|---|---|---|
| Both links active | EtherChannel operational | EtherChannel Operational |
| Same-VLAN ping | Successful | Successful |
| One member link disabled | Port-Channel remains up | Port-Channel remains up |
| Ping during link failure | Connectivity maintained | Connectivity maintained |
| Failed link restored | Both links bundled | Both links bundled |

## Link Failure Simulation

![Link Failure](PING_WITH_ONE_PORT_DOWN.png)

## Connectivity Test

![Link Restoration](PING_RESTORED.png)

[Back to Lab Overview](../README.md)
