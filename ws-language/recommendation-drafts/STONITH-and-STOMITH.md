# Recommendation: STONITH / STOMITH
January 2022

## Summary
| Term                                                         | Recommendation | Recommended Replacement Terms                    |
| ------------------------------------------------------------ | -------------- | ------------------------------------------------ |
| STONITH / STOMITH (Shoot the Other Node/Machine in the Head) | Replace        | TDTON / TDTOM (Take Down the Other Node/Machine) |

## Term
* STONITH (Shoot the Other/Offending Node in the Head)
* STOMITH (Shoot the Other/Offending Machine in the Head)

## Recommendation
Replace

## Recommended Replacement Terms
* TDTON (Take Down the Other/Offending Node)
* TDTOM (Take Down the Other/Offending Machine)

## Unsuitable Replacement Terms
TBD

## Use Context
In computing clusters, a failed or unresponsive node/machine can disrupt the entire setup and put data at risk.
To prevent this, clusters often have capabilities to fence-off failed or unresponsive nodes/machines from the others by deactivating them.
The term refers to the action undertaken to deactivate, power down, or otherwise disable the failed node/machine.

## Rationale for Replacement
STONITH and STOMITH use violent terminology. Since there are suitable alternatives that do not use violent language,
the INI recommends replacing STONITH and STOMITH wherever possible.

## Notes and Ideas from Discussion

(To be deleted when recommendation is finalized.)

Possible verbs:

* Prune
* Bounce
* Deadhead
* Alternative acronyms for STONITH/STOMITH 
* TDTON / TDTOM (Take Down The Other Node/Machine)
* ETON / ETOM (Erase the Other Node/Machine)

(Possibly could use "deactivate" or "disable" in place of "erase"?
Google [recommends](https://developers.google.com/style/word-list#letter-s) using "fence failed nodes," which seems inadequate.)
