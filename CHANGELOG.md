Unreleased - planned
--------------------
Organize output so the multithreading doesn't break up the results
Ability to search for specific CIDRs, example: -i 172.17.10.4 -c /24, this will search both the specific IP and /24. You can also just search the CIDR.
    Might do this to where either the entire CIDR range is searched or just the network ID
    *Add ipaddress module for this*

Version 2.2.1 - 2021-08-09
--------------------------
Fixed: ACL name parsing has been optimized


Version 2.2.0 - 2021-08-08
--------------------------
Added: Grabs the ACL the matching rule is part of


Version 2.1.3 - 2021-08-05
--------------------------
Added: Check for logs folder in log builder


Version 2.1.2 - 2021-07-28
--------------------------
Fixed: Core router discovery wasn't implemented
Added: Check for and create daily runtime folders to better organize the log outputs


Version 2.1.1 - 2021-07-26
--------------------------
Added: -V option to print version information


Version 2.1 - 2021-07-22
------------------------
Added: XMC API call for dynamic inventory


Version 2.0 - 2021-02-01
------------------------
Added: Multi-threading capabilities


Version 1.0 - 2020-06-12
------------------------
Initial release