# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


## backend  created ++++++++

mkdir fertilizer-tracker
cd fertilizer-tracker
npm init -y
npm install --save-dev hardhat
npx hardhat
npm install --save-dev @nomicfoundation/hardhat-toolbox
add hardhat.config.js
create contracts/FertilizerTracker.sol
create scripts/deploy.js
## runninf++++  termine 1
npm init -y
npm install express dotenv cors ethers
npx hardhat compile
npx hardhat node
# Open new terminal 2
npx hardhat run scripts/deploy.js --network localhost

# Open new terminal 3

## frontend creation ===================================

npm create vite@latest frontend -- --template react
cd frontend
npm install
npm install ethers
npm run dev
=================================


git add hardhat.config.js index.js meee.txt  node_modules package-lock.json package.json scripts test


git add hardhat.config.js index.js meee.txt package-lock.json package.json scripts test