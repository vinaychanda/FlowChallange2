# FlowChallange2

# ResoureOnCadance

Access modifiers in Cadence Flow blockchain refer to the keywords that are used to restrict the access to the functions and variables in a smart contract. They are used to specify the level of access that is granted to various users or contracts.


## Public

Functions and variables that are marked as public can be accessed from any account or contract. These are typically used to define the interface of the smart contract.

## Access(self)
The access(self) modifier allows a function to be called only by the same account that owns the smart contract.

## Access(contract)
The access(contract) modifier allows a function to be called only by a specific contract. 

## Pub(set)
The pub(set) modifier allows a variable to be publicly read and privately written. This means that anyone can read the value of the variable, but only the contract itself can change its value.
