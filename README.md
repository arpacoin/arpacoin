
ArpaCoin development tree

ArpaCoin is a PoS-based cryptocurrency.

ArpaCoin is dependent upon libsecp256k1.

Dynamic rewards
Block Spacing: 60 Seconds
Stake Minimum Age: 5 Hours

Port:   56631
RPC Port: 57631
Max POW blocks: 5000

ArpaCoin includes an Address Index feature, based on the address index API (searchrawtransactions RPC command) implemented in Bitcoin Core but modified implementation to work with the ArpaCoin codebase (PoS coins maintain a txindex by default for instance).

Initialize the Address Index By Running with -reindexaddr Command Line Argument.  It may take 10-15 minutes to build the initial index.


