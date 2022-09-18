**Description:**
An easy and secure way for governments to credit
carbon tax credit to business owners and individuals

**Transaction Flow**
1. User logs into site, signs in with blockchain wallet
2. User sees interface to submit type of claim (solar,
wind, geothermal, water) - very basic can be
expanded
3. The Inspector, which is given permission to certify the
energy conversion by the government approves or
rejects the upgrades
4. Once approved, the user is given carbon tax credits
5. The user can then redeem carbon tax credits

![image](https://user-images.githubusercontent.com/100609687/190924952-4175d4ae-4e61-4cae-a6d8-8ff012d9750b.png)

**Transaction flow (detailed)**
1. Government deploys contract
2. Government sets Inspector by calling setInspector(< address >)
3. User creates claim using createClaim( <renewable energy type>)
4. Inspector approves claim by using approveClaim()
5. Contract mints carbon credit erc20 to claimant
6. User calls redeemCredits() in mock tax credit program which subtracts token
balance from tax amount due, carbon credits are then burned

![image](https://user-images.githubusercontent.com/100609687/190924992-567bf597-c498-4b52-ae67-bc685854a74d.png)
![image](https://user-images.githubusercontent.com/100609687/190925002-a1fed611-027a-48d9-a174-aa65818576a9.png)

**What we will continue:**
1. Making contract safer/ more secure
2. Optimizing gas
3. Adding government/ inspector interfaces to website

**our backend contract: 
renewableEnergy.sol**

**frontend:
renewable-energy**
