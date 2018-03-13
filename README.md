ClintonCash staging tree 1.0.0
===============================

https://www.clintoncash.net


What is ClintonCash?
----------------

ClintonCash is a crypto-currency built upon the features of Bitcoin and Dash to serve as a medium of exchange free of government interference. Beyond this, ClintonCash is a community-driven endeavor to use the power of the blockchain to spur a new investigation of Hillary Clinton’s crimes and put her in prison, where she belongs. ClintonCash will bring an end to corrupt political elitism. 


###### Proof-of-Work Algorithm: Lyra2REv2
###### Block Max Size: 2 MB
###### Block Time: ~120 seconds
###### Block Reward: 100 CCASH
###### Coin Maturity: 100 blocks
###### Maximum Coin Supply: 20 Million
###### Difficulty Retargeting: DGWv3
###### Masternodes: Enabled
###### Masternodes Collateral: 1000 CCASH
###### Masternodes Payments Start Block: 0
###### Masternode Reward: 45% of block reward

For more information, as well as an immediately useable, binary version of
the ClintonCash software, see https://www.clintoncash.net.


License
-------

ClintonCash is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is meant to be stable. Development is normally done in separate branches.
[Tags](https://github.com/clintoncash) are created to indicate new official,
stable release versions of ClintonCash.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](/doc/unit-tests.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`

There are also [regression and integration tests](/qa) of the RPC interface, written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/qa) are installed) with: `qa/pull-tester/rpc-tests.py`

The Travis CI system makes sure that every pull request is built for Windows
and Linux, OS X, and that unit and sanity tests are automatically run.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.
