# aleo-voting-system
 

This is a private voting system that allows users to cast their votes anonymously and securely using zero-knowledge cryptography. It is built using the [Aleo platform] and the [Leo programming language].

## Features

- Supports multiple candidates and ranked-choice voting
- Uses zero-knowledge proofs to verify the validity of the ballots and the signatures
- Uses proof-of-succinct-work consensus protocol to maintain the state of the Aleo blockchain
- Uses snarkVM to execute zero-knowledge proofs in an efficient and secure manner

## Usage

To run this application, you will need to have the following tools installed:

- [Aleo Studio IDE] or [Leo CLI tool]
- [Aleo Testnet] or [Aleo Playground]

To run this application using the Aleo Studio IDE, follow these steps:

- Clone this repository or download the source code as a zip file
- Open the folder in the Aleo Studio IDE
- Open the `main.leo` file and click on the `Run` button
- The IDE will automatically compile the code, generate the input and output files, and run the application
- You can view the results in the `output.json` file or in the console

To run this application using the Leo CLI tool, follow these steps:

- Clone this repository or download the source code as a zip file
- Open a terminal and navigate to the folder
- Run `leo build` to compile the code
- Run `leo setup` to generate the proving and verification keys
- Run `leo run` to run the application
- You can view the results in the `output.json` file or in the terminal

To test this application using the Aleo Testnet or the Aleo Playground, follow these steps:

- Clone this repository or download the source code as a zip file
- Open a browser and navigate to the [Aleo Testnet] or [Aleo Playground] website
- Upload the folder or drag and drop it into the website
- The website will automatically compile the code, generate the input and output files, and run the application
- You can view the results in the `output.json` file or in the website

## Dependencies

This application depends on the following packages:

- [std.vote]: A standard library package that provides basic functionality for creating and verifying vote circuits
