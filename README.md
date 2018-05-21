# MonetaryCoin-Audit

The following repository contains the full audit report for the MonetaryCoin (MCoin) token and crowdsale, written in the Solidity language for the Ethereum platform.
The full audit report includes a technical overview of the platform, its functionality, and the API. 
In addition, it brings a list of comments and suggestions regarding the security, design, and implementation of the contracts.

Commit hashes pertain to the git repository hosting the contracts.

This README file contains the list of changes peformed by the MCoin team following receiving the audit report. 
Satisfactory responses were given to non-changed items.
The list of changes was examined with respect to commit 8b11670.

## List of Changes Post-Audit
1.3.	Added in commit 2fc9908.

1.4.	Fixed in commit 22fdddd5.

1.7.	Added in commit 97db06d8.

1.9.	Changed in commit 5b267811.

1-View functions.	Added in commit 81cf8ac6.

1.10.	Fixed in commit d88c9c9b.

1.11. 

  1. Added tests in commit 88f3c57c.
  
  2. Added special solidity test in commit 6642946b.

2.1.	Added in commit 22fb3e5d.

2.2.	Fixed in commit a29b87b4.

3.1.	Added with a test in commit cead42b6.

3.3.	Added in commit 3639bf44.

3.6.	Added to M5LogicMock3.sol and M5tokenMock.sol in commit 5619ae3b.

3.12.	Revised `getM5Reward` function in commit 180b688c and nitpicky fix in commit 7bf502db.

3.13.	Added ownership renouncing in merge from openzeppelin-solidity commit 8457e992.

3.14.	Added with test in commit 2bfe2026.

3.15.	Removed burnable in commit 0a1042bc.

4.1.	Added some documentation in commit d96f5175.

4.2.	Split into separated contract in commit 76df3a32.

4.4.	Added with a test in commit 19c33a86.

5.1.	Fixed in commit e1aa449d.

5.2.	Added in commit 61a6ead1.

5.4.	Added in commit 195f306c.

5.5.	Fixed - Removed `require(startTimestamp < block.timestamp);` in commit 1656165b. The auction is open for commitments from the moment it is created.

5.7.	Fixed in commit 85a970d6.
