# BLRKGen (BitLocker Recovery Key Generator)
Bash script to generate a list of all possible legal BitLocker Recovery Keys.

This script will take forever to create a word list of all recovery keys.
I recommend you edit the script as described in the comments of ths script, so that
you can reduce the keyspace to just the groups of six digits of the recovery key that
you can no longer read. Maybe you wrote it down wrong or spilt coffee on the printout.

Usage:

"./BLRKGen" or "bash BLRKGen" to output to the terminal or to pipe to another program

or

"./BLRKGen > list.txt" or "bash BLRKGen > list.txt" to create a wordlist file

Send BitCoins to: 1AmNe5iAYfYCGYFq7vpLWL4XRFxe21hh9D
