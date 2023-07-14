# Kanshi (KSH) Solidity Contract

This contract represents a basic token named Kanshi (KSH) contract in Solidity.

## State Variables

- `tokenName`: The name of the token.

- `tokenAbbrv`: The abbreviated name or symbol of the token.

- `totalSupply`: The total supply of the token.

- `balances`: A mapping of addresses to their corresponding token balances.

## Functions

- `mint`: Mints new tokens and assigns them to the specified address.

- `burn`: Burns existing tokens from the specified address.

## Additional (For Metacrafters Requirement)

- `transactionID`: Just a custom identifier for the application.

- `LogString`: Emitted when a string message needs to be logged.

- `logTransactionID`: Logs the application/transaction ID through the `LogString` event.
