# Task : Create A Block with Tweaking scratch-gui and scratch-vm

![scratchImg](https://user-images.githubusercontent.com/95914822/173211872-8a1eec33-d842-4688-b631-e3d62f25a585.png)

## Install
### Git | NodeJS | NPM | Java | Python 2.x | VS Code

## Get Started
mkdir Scratch

cd Scratch

git clone https://github.com/llk/scratch-gui

git clone https://github.com/llk/scratch-vm 

git clone https://github.com/llk/scratch-blocks

cd scratch-vm

npm install

npm link

npm run watch

cd ../scratch-blocks

npm install

npm link

cd ../scratch-gui

npm install

npm link scratch-vm scratch-blocks

npm start

http://localhost:8601

## Allow your changes
### scratch-vm: npm run watch.
### scratch-blocks: npm run prepublish command to rebuild scratch-blocks.(Make sure you run the command from the scratch-blocks directory!) 

## Reference
### https://github.com/LLK/




