# Assignment--Module-18

## Purpose

The purpose of this assignment is to build a blockchain based application with a user friendly web interface.

The application allows users to send amounts (transactions) between one account and another, specifying the amount.

This transaction is then mined in a block and added to a blockchain. The blockchain, or list of blocks is displayed, including the sender, receiver, amount, hash and nonce.

Finally, the blockchain is able to be validated by the user to ensure no manipulation of the chain has occured.

---

## Process

- A new class - Record - was added to the code, with variables for sender, receiver and amount.

- The Block class was revised to include an instance of the Record class.

- The streamlit application was revised to include the fields "sender", "receiver" and "amount". The user is able to enter information into these fields as part of creating a block.

- When a new block is created, it will now include an instance of a Record class, taking the parameters from the "sender", "receiver" and "amount" fields the user entered on the streamlit web interface.

- The streamlit app was run using
  `streamlit run pychain.py`.

- Three blocks were added successfully.

- The blockchain was validated as True.

---

### Pychain Streamlit application:

The below image shows the running streamlit pychain application with only the genesis block present.

![](Images\pychain_clean.JPG)

---

### Pychain Ledger:

Three transactions were sent and the blocks mined. The below images shows the ledger of blocks.

![](Images\pychain_blocks_added.JPG)

Here is an expanded view of the blockchain to display all fields in each block.

![](Images\expanded_block_list.JPG)

---

### Pychain Validation:

The blockchain has been validated as True, meaning no manipulation or modification of the blockchain has occurred.

![](Images\pychain_validate_true.JPG)
