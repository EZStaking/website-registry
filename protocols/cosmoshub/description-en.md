<p>
    The Cosmos network consists of many independent, parallel blockchains, called zones, each powered by classical Byzantine fault-tolerant (BFT) consensus protocols like Tendermint (already used by platforms like ErisDB). Some zones act as hubs with respect to other zones, allowing many zones to interoperate through a shared hub. The architecture is a more general application of the Bitcoin sidechains concept, using classic BFT and Proof-of-Stake algorithms, instead of Proof-of-Work. Cosmos can interoperate with multiple other applications and cryptocurrencies, something other blockchains can’t do well. By creating a new zone, you can plug any blockchain system into the Cosmos hub and pass tokens back and forth between those zones, without the need for an intermediary.
</p>

<p>
    While the Cosmos Hub is a multi-asset distributed ledger, there is a special native token called the atom. Atoms have three use cases: as a spam-prevention mechanism, as staking tokens, and as a voting mechanism in governance.
</p>

<p>
    As a spam prevention mechanism, Atoms are used to pay fees. The fee may be proportional to the amount of computation required by the transaction, similar to Ethereum’s concept of “gas”. Fee distribution is done in-protocol and a protocol specification is described here.
</p>

<p>
    As staking tokens, Atoms can be “bonded” in order to earn block rewards. The economic security of the Cosmos Hub is a function of the amount of Atoms staked. The more Atoms that are collateralized, the more “skin” there is at stake and the higher the cost of attacking the network. Thus, the more Atoms there are bonded, the greater the economic security of the network.
</p>

<p>
    Atom holders may govern the Cosmos Hub by voting on proposals with their staked Atoms.
</p>