# aeon-check

Initial design thoughts https://en.opensuse.org/Portal:Aeon/DevelopmentThoughts#aeon-check. This should be considered this project's long term goal.

Short term goal - Local checks only directly executing fixes for resolving specific bugs in Aeon RC3 and later

## Bugs Addressed
- Check existing Aeon Default Mode installations and confirm the TPM enrolment is using pcrlock not PCR hashes after incase enrolment steps occurred in an imperfect order (boo#1228416)
