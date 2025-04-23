# Daowakanda Dev Task

This dev task requires you to call the `buyListing` method of an existing smart contract with Application ID `2948568810` using the Application Spec in `src/client.ts`; Successfully calling this smart contract method will make you receive an asset.
For reference, see this example: https://github.com/Algorand-Africa/peer-coding-session-2/blob/main/client/src/index.ts

To compile and run, run this command: `npm run development`

In order to sucessfully call the 'buyListing' method, you must:
- Ensure that you're opted into the ASA ID `2948546348`. The ASA ID has been added to the `src/index.ts` file for you already.
- Pass a payment transaction as an argument to the method call. The payment transaction should pay an amount of `0.02 Algos` into the smart contract's address. The payment transaction should also have a flat fee of `0.02 Algos`. If these conditions are not met, the method call will fail.

The application id can also be found in the `src/index.ts` file.

To complete this dev task, you must create a fork of the repository and commit your answer. A link to your fork should be
submitted on DaoWakanda to this link https://www.daowakanda.org/developers/.

Ensure that you do not push your mnemonic key to GitHub! 

Add your address to the top of the `src/index.ts` file as a comment as the address can be used to confirm that you successfully claimed the ASA.

NB: You are to claim the asset on the Mainnet.
