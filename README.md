# Trading Card Game Frontend

This directory contains the frontend components for the Trading Card Game project. These components are responsible for the user interface and interaction with the smart contracts deployed on the blockchain.

## Summary

The frontend components are designed to provide a user-friendly interface for players to interact with the game's features, including battling, card trading, and card display. Below is a brief overview of the key components:

1. **BattleArena.jsx**:
    - Component responsible for displaying the battle arena where players can initiate and view card battles.
    - Allows players to select cards for battle and displays the outcome of battles.

2. **CardDisplay.jsx**:
    - Component for displaying individual trading cards.
    - Provides a visual representation of the cards owned by the player or available for trading.

3. **TradeInterface.jsx**:
    - Interface component for facilitating card trading between players.
    - Allows players to initiate and confirm trades of their NFT cards with other players.

4. **ethersInit.js**:
    - Utility file for initializing the Ethereum provider and setting up connections to the smart contracts.
    - Responsible for initializing the Ethereum wallet provider using Ethers.js.

5. **ipfs.js**:
    - Utility file for interacting with the InterPlanetary File System (IPFS).
    - Provides functions for uploading and retrieving files from IPFS, which can be useful for storing metadata or images associated with NFTs.

## Setup and Usage

1. Ensure that Node.js and npm are installed on your system.
2. Clone the project repository and navigate to the `frontend` directory.
3. Install dependencies by running `npm install`.
4. Start the development server using `npm start`.
5. Access the application in your web browser at the specified URL (typically `http://localhost:3000`).
6. Interact with the game features through the provided user interface components.

## Additional Notes

- Customize the components as needed to match the desired user experience and game mechanics.
- Test the frontend components thoroughly to ensure proper integration with the smart contracts and smooth gameplay for users.

## License

The frontend components are provided under the MIT License. See individual files for details.
