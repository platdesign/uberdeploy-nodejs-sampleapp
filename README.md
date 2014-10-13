#uberdeploy-nodejs-sampleapp

A litte simple sample how to deploy a nodejs-app with [uberdeploy](https://github.com/platdesign/uberdeploy).

##Install

**1. Copy command and execute in a shell**

	git clone https://github.com/platdesign/uberdeploy-nodejs-sampleapp &&  cd uberdeploy-nodejs-sampleapp && rm -rf .git

	
**2. Rename project folder**

Otherwise your project would be named: `uberdeploy-nodejs-sampleapp` ;)
	
**3. Create the uberdeploy project**

	uberdeploy create
	
**4. Configure some things**

- **deploy/post-receive** Edit `PORT` and `DOMAIN` to your needs.
- **index.js** Edit `PORT` (same value as in *deploy/post-receive*)

**5. Deploy your app**

	uberdeploy deploy
	
**6. Done =)**


If there are any questions or suggestions feel free to get in touch. =)



##Contact##

- [mail@platdesign.de](mailto:mail@platdesign.de)
- [platdesign](https://twitter.com/platdesign) on Twitter