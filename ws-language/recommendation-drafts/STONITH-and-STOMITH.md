# Recommendation: STONITH / STOMITH
January 2022

## Summary
| Term                                                         | Recommendation | Recommended Replacement Terms              |
| ------------------------------------------------------------ | -------------- | ------------------------------------------ |
| STONITH / STOMITH (Shoot the Other Node/Machine in the Head) | Replace        | ETON / ETOM (Erase the Other Node/Machine) |

## Term
* STONITH (Shoot the Other Node in the Head; Shoot the Offending Node in the Head)
* STOMITH (Shoot the Other Machine in the Head; Shoot the Offending Machine in the Head)

## Recommendation
TBD (probably replace?)

## Recommended Replacement Terms
* ETON (Erase the Other/Offending Node)
* ETOM (Erase the Other/Offending Machine)

(Possibly could use "deactivate" or "disable" in place of "erase"?)

## Unsuitable Replacement Terms
TBD

## Use Context
In computing clusters, a failed or unresponsive node/machine can disrupt the entire setup and put data at risk.
To prevent this, clusters often have capabilities to fence off failed or unresponsive nodes/machines from the others by deactivating them.
The term refers to the action undertaken to deactivate, power down, or otherwise disable the failed node/machine.

## Rationale for Replacement
STONITH and STOMITH use violent terminology. Since there are suitable alternatives that do not use violent language,
the INI recommends replacing STONITH and STOMITH wherever possible.
