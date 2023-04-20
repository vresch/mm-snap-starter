# MetaMask Snaps - High Low Game
MetaMask snap + web UI to let you play a guessing game and keep score. Serves as a learning resource to building with MetaMask snaps.

Please reference this [live coding session](https://www.youtube.com/watch?v=7J5NBJRABu0) for a walkthrough :)



## Getting set up
1. clone repo, yarn install
2. `yarn snap-dev` to start snap
3. create a `packages/demo/.env.local` and populate the post at which snap is being served, as well as Infura project info (used to upload images to IPFS):
```
NEXT_PUBLIC_SNAP_ID=local:http://localhost:8086
## OPTIONAL: only if you want to enable uploading to IPFS with Infura
NEXT_PUBLIC_INFURA_ID=<fill here>
NEXT_PUBLIC_INFURA_API_KEY=<fill here>
```
4. `yarn demo-start` to start nextjs web app


## Resources:
- IPFS: https://www.becomebetterprogrammer.com/upload-files-using-react-ipfs-infura/
- ens: 
  - https://github.com/ensdomains/ensjs
  - https://docs.ens.domains/dapp-developer-guide/resolving-names#reverse-resolution
- web3react: https://dev.to/yakult/how-to-use-web3-react-to-develop-dapp-1cgn
