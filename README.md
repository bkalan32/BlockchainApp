# PyChain Ledger

This repository contains a Python implementation of a blockchain-based ledger called PyChain. It allows you to store transaction records in a decentralized and tamper-proof manner. The PyChain ledger utilizes the Streamlit framework for the user interface.

## Features

- Creation of a Record Data Class to define the structure of financial transaction records.
- Modification of the Block Data Class to store Record Data instead of generic data.
- Addition of user input areas in the Streamlit interface to capture sender, receiver, and amount for each transaction.
- Validation of the blockchain and display of the ledger using the Streamlit application.
- Proof-of-work mechanism to ensure the security and integrity of the blockchain.

## Getting Started

To get started with the PyChain Ledger, follow these steps:

1. Clone this repository to your local machine.
2. Install the necessary dependencies by running `pip install -r requirements.txt`.
3. Run the Streamlit application by executing `streamlit run pychain.py` in your terminal.
4. Access the PyChain Ledger through your web browser at the provided URL.

## Usage

1. When the Streamlit application is running, you will see a user interface for the PyChain Ledger.
2. Enter the details of the transaction in the input areas: sender, receiver, and amount.
3. Click the "Add Block" button to add the transaction to the ledger.
4. The ledger will be displayed in a table format, showing the blocks and their details.
5. Use the sidebar to adjust the block difficulty and view specific blocks.
6. Click the "Validate Chain" button to verify the validity of the blockchain.

## Screenshots

Here are some screenshots of the PyChain Ledger in action:

[Add Block](screenshot_add_block.png)
![Add Block](screenshot_add_block.png)

[Blockchain Validation](screenshot_blockchain_validation.png)
![Blockchain Validation](screenshot_blockchain_validation.png)

## Contributing

Contributions to the PyChain Ledger are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

The PyChain Ledger is released under the [MIT License](LICENSE).

