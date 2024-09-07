TO run all projects then run "yarn start"

Run a Specific Project:
yarn workspace backend start
yarn workspace psl-customer start
yarn workspace psl-driver start

Step 2: Run a Single Project Using Lerna
npx lerna run start --scope=backend
npx lerna run start --scope=psl-customer
npx lerna run start --scope=psl-driver


If you find yourself frequently running individual projects
yarn start:backend
yarn start:psl-customer
yarn start:psl-driver
