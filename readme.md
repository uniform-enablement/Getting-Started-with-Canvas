## Prerequisites

You are expected to have all of these accounts created before you can get started with Uniform.

- GitHub (Free) - https://github.com
- Netlify (Free) - https://netlify.com/
- BigCommerce (Free Trial) - https://www.bigcommerce.com/essentials/free-trial/
- Uniform (Community Tier) - http://uniform.app/
- Contentful (Community Tier) - https://www.contentful.com/pricing/

## Create an account in Uniform, and Create your First Project

![image](https://user-images.githubusercontent.com/90791205/142446997-f2e384aa-b6a6-44c1-a1dc-83a33062c6e8.png)

Give your project a name and select the first option.

![image](https://user-images.githubusercontent.com/90791205/142447119-922958f7-4eff-4407-a144-e748f962105a.png)

Next Select your Deployment Platform

![image](https://user-images.githubusercontent.com/90791205/142447218-41dc5759-d44f-4ad0-8c96-2a4e01c976fd.png)

Next Login to Contentful

![image](https://user-images.githubusercontent.com/90791205/142447351-ebc9f872-4ca2-4740-88d9-376048880608.png)

Choose your Organization and create a new space in it.

![image](https://user-images.githubusercontent.com/90791205/142447488-4bb9952b-ab04-4335-ac34-9cd343d8f5b2.png)

Then Install Uniform Optimize App and Uniform Starter Content, by clicking on every step, until it completes and you will see all three boxes turn green.

![image](https://user-images.githubusercontent.com/90791205/142447747-1bb9ef00-a1dd-405a-aa34-479f25a47df3.png)

Proceed to next Step, and Install Uniform App in BigCommerce.

![image](https://user-images.githubusercontent.com/90791205/142447858-418b057b-2f35-4645-91c3-0aa83d7723e7.png)

![image](https://user-images.githubusercontent.com/90791205/142448014-363112dc-f2a9-4762-9308-5deb6d42887a.png)

Once you complete that Step, Continue.

In the next Step we will be deploying our website to Netlify

![image](https://user-images.githubusercontent.com/90791205/142448122-b57d57dc-d136-4a28-9a29-87aac87aea4b.png)

Follow the steps in Netlify:

- Connect to Github
- All the fiels will be populated with Environment Variables so just click Save and Deploy

![image](https://user-images.githubusercontent.com/90791205/142448340-334e620d-ce91-4617-ae56-5f7329852374.png)

While Deployment is in progress, lets go ahead and add a WebHook.

Inside Netlify under Build & Deploy > Continuous Deployment > Build Hook

![image](https://user-images.githubusercontent.com/90791205/142449116-a694fba6-2bed-4180-9fc7-ba237ffda79a.png)

For an easier navigation

https://app.netlify.com/sites/{your-site-name}/settings/deploys#build-hooks

Create a webhook

![image](https://user-images.githubusercontent.com/90791205/142449194-b5584d69-79b1-4ab0-b1fc-b569c19efa14.png)

Copy the generated web hook (dont try using this webhook it is no longer available)

![image](https://user-images.githubusercontent.com/90791205/142449226-94252ca0-8cce-4763-8905-f8bbc50f1124.png)

Navigate over to Uniform and paste the webhook and add it.

![image](https://user-images.githubusercontent.com/90791205/142449625-777ad2e8-8abd-4678-9ffd-ca0940643088.png)

Once you are done with that, by then the build should be completed and you should be able to view your website deployed.

![image](https://user-images.githubusercontent.com/90791205/142449818-f085086e-a002-46c4-8e5a-f70e5717d240.png)

This Completes the tutorial
