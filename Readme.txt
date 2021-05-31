For First Time Users follow the instructions

For Package and Deployment

1. GIT clone from the repo
2. npm install (Will install all the required dependencies from package.json

Fresh installation commands

1. npm init
2. npm install webdriverio --save-dev
3. npm install @wdio/cli
4. npx wdio run wdio.conf.js (Select Type Script in this step if you want to 	  
    use TS)
5. npm install typescript --save-dev
6. npx tsc--init
7. npm i tslint --save-dev
8. npx tslint --init
9. To Run the script use below cmd
	npx wdio wdio.conf.ts   ---> for Type Script
      npx wdio wdio.conf.js.  ---> for Java Script

Or you can modify package.json
	"test" : "npx wdio wdio.cong.ts"
	"smoketest": "npx wdio wdio.conf.ts"

To Run the script based on the package.json config

	> npm run test

To run smoke test

	> npm run smoketest



