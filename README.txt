REMIX DEFAULT WORKSPACE

Remix default workspace is present when:
i. Remix loads for the very first time 
ii. A new workspace is created with 'Default' template
iii. There are no files existing in the File Explorer

This workspace contains 3 directories:

1. 'contracts': Holds three contracts with increasing levels of complexity.
2. 'scripts': Contains four typescript files to deploy a contract. It is explained below.
3. 'tests': Contains one Solidity test file for 'Ballot' contract & one JS test file for 'Storage' contract.

SCRIPTS

The 'scripts' folder has four typescript files which help to deploy the 'Storage' contract using 'web3.js' and 'ethers.js' libraries.

For the deployment of any other contract, just update the contract's name from 'Storage' to the desired contract and provide constructor arguments accordingly 
in the file `deploy_with_ethers.ts` or  `deploy_with_web3.ts`

In the 'tests' folder there is a script containing Mocha-Chai unit tests for 'Storage' contract.

To run a script, right click on file name in the file explorer and click 'Run'. Remember, Solidity file must already be compiled.
Output from script will appear in remix terminal.

Please note, require/import is supported in a limited manner for Remix supported modules.
For now, modules supported by Remix are ethers, web3, swarmgw, chai, multihashes, remix and hardhat only for hardhat.ethers object/plugin.
For unsupported modules, an error like this will be thrown: '<module_name> module require is not supported by Remix IDE' will be shown.




## Winner Selection in Lucky draw using blockchain solidity
Here, i'm using the remix ide to construct this project.
A good and reliable software for solidity.

In this project, minimum participants i have taken as 3.
As the number of participants will be less than the minimum, then Lucky draw will not happen.

I have taken the manager variable as the global varible, which will store the address of the manager.

As the participants will transact some ether into manager's account, then after gaining the ether from the minimum of 3 participants, 
manger will able to select the winner by calling the SelectWinner function of the lucky.sol.

After execution of the SelectWinner program, winner is selected and that winner will able to gain all the ethers gained by the manger during the registration of the 
participants...................
