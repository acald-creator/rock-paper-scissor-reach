## Women Who Code Bounty Hack
> Algorand Blockchain

## Details
To run, there is already an executable binary within the repository that will automatically generate the necessary tools to run the program within a dockerized environment.

Each folder is a section of a tutorial completed from Reach.sh documentation on how to setup Rock, Paper, Scissors.

## Steps
Ensure that you're using the correct and latest version of `reach`.

`./reach update`

Enter each of the folder and run `../reach run` so that `reach` can compile and build a Docker image.

Example:

```bash
../reach run
Sending build context to Docker daemon  26.62kB
Step 1/3 : FROM reachsh/runner:0.1.10
 ---> f6a2acea3760
Step 2/3 : COPY . /app
 ---> Using cache
 ---> abb001710b6f
Step 3/3 : CMD ["index"]
 ---> Using cache
 ---> 755d57818f4a
Successfully built 755d57818f4a
Successfully tagged reachsh/reach-app-2-tutorial:0.1.10
Creating 2022-04-16t03-01-56z-jod3_reach-app-2-tutorial_run ... done

> index
> node --experimental-modules --unhandled-rejections=strict index.mj
```

The last folder shows the completed tutorial, which includes the backend and the frontend that also allows you to connect to a support Algorand wallet.

To get started, you will need an Algorand wallet. For my project, I am using MyAlgoConnect Wallet.

You will also need some Algos in order to place a wager.

To do this, access Algorand testnest faucet after you have setup a wallet and send some Algos to your testnet wallet.

https://bank.testnet.algorand.network/

You may need two separate wallets in order to test the game.
### Roadmap
@TODO implement the client in Go