# MintTutorial

This is a tutorial for mint DMTK, the first dmint token.

# Link

https://twitter.com/DMTK_AMC20

# 1.Download

Download this github repo:

git clone https://github.com/DMTKamc20/MintTutorial.git


# 2.Mint By Sats
This is the step-by-step guide for mint dmtk3

1. Open https://satsx.io/inscribe/atomicals and connect you wallet.

2. Choose Dmint , and our container name is "dmtk".

3. Upload you json file  item_dmtk3.json.

4. Fill in Sats such as 50 based the real-time sats in the upper right corner.

5. Click the "Preview" button as shown below.If the submission fails, it means that this number has been mint. Please select another number and upload the corresponding json file.
 
![1701786388263](https://github.com/DMTKamc20/MintTutorial/assets/152500101/7a63fc7f-52ef-4cbd-86fd-0afb9f6b93ae)


6. Click the "inscribe" button as shown below, confirm the transaction in the wallet and wait for it to be uploaded to the chain.
![1701780481697](https://github.com/DMTKamc20/MintTutorial/assets/152500101/fa58b63c-c78a-4098-a8bb-a6a895c7fbf1)




# 3.Mint By Command Line

If you have experience using atomical-js tools. You can mint as follows：

1. Place the dmtk_json folder in the ATOMICAL_JS directory.

2. Choose you item id and run command:

3. yarn cli mint-item "#dmtk" "dmtk1" "./dmtk_json/item-dmtk1.json" --satsbyte=30
