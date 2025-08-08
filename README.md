# Steps to deploy
### Step 1: `npm install`
### Step 2: Install pkg using: `npm i -D pkg`
### Step 3: Create a binary using: `npx pkg -t node18-alpine app.js`
### Step 4: Build the enclave image using: `sudo docker run -it --privileged -v `pwd`:/app/mount marlinorg/enclave-builder`
### Step 5: Change permission of `enclave.eif` from root to user using `sudo chown <userName> -R enclave.eif`
### Step 6: Upload it for downloading (Already added in github releases)
### Step 7: Deploy : 
### Step 8: Use: curl <IP>:4000
