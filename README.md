**ERC20 and Vault Contracts**

This repository contains the implementation of ERC20 token and a Vault smart contract in Solidity. Below are brief descriptions of each contract and how to use them.

### ERC20 Token Contract

The ERC20 token contract is a standard implementation of the Ethereum token standard. It allows for the creation and management of tokens following the ERC20 specification, enabling seamless integration with various platforms and exchanges. Key features of this contract include:

- **Token Creation**: Deploy the contract to create a new ERC20 token with specified initial supply, name, symbol, and decimals.
- **Token Transfer**: Transfer tokens between addresses.
- **Approval Mechanism**: Approve addresses to spend tokens on behalf of the owner.
- **Transfer From**: Execute transfers on behalf of the token owner, given approval.
- **Balance Inquiry**: Check the balance of any address holding the token.

### Vault Contract

The Vault contract provides a secure way to store ERC20 tokens, ensuring controlled access to the stored tokens. It incorporates features such as time-based locking and multi-signature functionality to enhance security. Key features of this contract include:

- **Token Deposit**: Deposit ERC20 tokens into the vault for safekeeping.
- **Token Withdrawal**: Withdraw tokens from the vault, subject to specified conditions (e.g., time lock or multi-signature approval).
- **Time-Based Locking**: Set time locks on deposited tokens, restricting withdrawals until a specified time has elapsed.
- **Multi-Signature Approval**: Require multiple signatures from authorized parties to approve token withdrawals, enhancing security and control.

### Usage

1. **Deployment**: Deploy the ERC20 token contract by specifying initial parameters such as supply, name, symbol, and decimals. Deploy the Vault contract to begin secure token storage.

2. **Token Management**: Use the ERC20 token contract to manage token transactions, including transfers, approvals, and balance inquiries.

3. **Vault Operations**: Deposit ERC20 tokens into the Vault contract for safekeeping. Set time locks or multi-signature requirements as needed. Withdraw tokens according to the specified conditions.

