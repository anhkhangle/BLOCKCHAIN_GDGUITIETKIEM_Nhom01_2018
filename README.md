# Seminar_Nhom01
Blockchain-based application for deposit in bank

SETUP

Step 1: Install testrpc, Truffle Framework and IPFS.

Step 2: Run git clone https://github.com/anhkhangle/BLOCKCHAIN_GDGUITIETKIEM_Nhom01_2018/

Step 3: Run npm install inside the directory.

Step 4: Run testrpc in a new terminal or Git Bash.

Step 5: Run IPFS daemon config:

ipfs config --json API.HTTPHeaders.Access-Control-Allow-Origin "[\"*\"]"

ipfs config --json API.HTTPHeaders.Access-Control-Allow-Credentials "[\"true\"]"

ipfs daemon

Step 6: Run IPFS library support package:

npm install --save ipfs-api

Step 7: Run truffle deploy to build and deploy application as well as contract.

Step 8: Run npm run dev and go to locahost:8080.

License

SGU License

The following people have been the contributors for the project.

Ngo Tran Thien An

Vo Tan Hieu

Le Tran Anh Khang

