# DAOTown - Build DAOs Instantly!

DAOTown revolutionizes DAO management by eliminating technical barriers, enabling seamless governance and tokenomics.

Managing DAOs traditionally requires technical expertise, limiting participation. Our platform simplifies these processes using decentralized infrastructure, making DAO management more accessible, effective, and intuitive for everyone.

## Technology Stack 🧰

- Solidity
- ethers.js
- Next.js
- React.js
- Foundry
- OpenZeppelin
- RainbowKit
- TypeScript
- JavaScript
- Chakra UI
- Lighthouse Storage (IPFS Gateway)

## Setting Up Foundry 🚧

### Prerequisites

Before starting, ensure the following are installed:

- Follow the [Foundry documentation](https://book.getfoundry.sh/) for installation instructions.

For Windows users, it is recommended to use Windows Subsystem for Linux (WSL) to set up Foundry.

### Getting Started

#### Cloning the Repository

1. Clone the DAOTown repository:

```bash
git clone https://github.com/AkshayS734/DAOTown
```

2. Navigate to the `contracts/` directory:

```bash
cd DAOTown/contracts/
```

#### Setting Up Environment Variables

1. Create a file named `.env` in the contracts directory.

2. Configure the `.env` file according to the provided `.env.example` file.

#### Installing Dependencies

Install the necessary dependencies for the Foundry setup:

```bash
forge install
```

#### Building the Project

Build the project with the following command:

```bash
make build
```

#### Deployment

The Makefile is set up for deployment on NeoX T4 Testnet.

```bash
make deploy ARGS="--network neox"
```

## Frontend Setup 🚧

**Note:** Update the compiled ABIs of the contracts in the `/frontend/src/utils/abis/` directory.

1. From the root, navigate to the `frontend/` directory:

```bash
cd DAOTown/frontend/
```

2. Create a `.env` file in the root directory of the project:

```bash
touch .env
```

3. Refer to `.env.example` to update the `.env` file.

4. Install Dependencies:

```bash
yarn
```

5. Run the project at `localhost:3000`:

```bash
yarn run dev
```



<!-- ## Deployed & Verified contracts on NeoX Network -

- DAOManager.sol: [0x...](#)
- GovernanceToken.sol: [0x...](#)
- CreateGovernanceToken.sol: [0x...](#) -->
