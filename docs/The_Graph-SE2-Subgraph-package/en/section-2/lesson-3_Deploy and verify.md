## Deploy and verify

### ✅ Deploy!

Now we can deploy to our testnet of choice... in this example we will deploy to sepolia.

```
yarn deploy --network sepolia
```

![](/public/images/The_Graph-SE2-Subgraph-package/section-2/Lesson3-1.png)

If all is well you should see the following success output.

```
deploying "YourContract" (tx: 0xf404021d736271a7a0a84d124ed35250c533efe37c1775367b6510a8836bf0bd)...: deployed at 0x541D469C06990B7F0bd5103b57997cE8a39C050c with 605281 gas
📝 Updated TypeScript contract definition file on ../nextjs/generated/deployedContracts.ts
```

#### ✅ Verification

```
yarn verify --network sepolia
```

![](/public/images/The_Graph-SE2-Subgraph-package/section-2/Lesson3-2.png)

You should see the following successful output...

```
verifying YourContract (0x541D469C06990B7F0bd5103b57997cE8a39C050c) ...
waiting for result...
 => contract YourContract is now verified
```
 
 You can also check your contract was successfully on etherscan. [Here](https://sepolia.etherscan.io/address/0x541D469C06990B7F0bd5103b57997cE8a39C050c#code) is the one I deployed and verified.

