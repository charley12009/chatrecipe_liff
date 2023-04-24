# Deploy LINE Front-end Framework (LIFF) Starter on Render

This repo can be used to deploy LINE Front-end Framework (LIFF) Starter in the [line-liff-v2-starter](https://github.com/line/line-liff-v2-starter) on [Render](https://render.com/). 

## Prerequisites
Make sure you have the following:
- A LINE Login channel with the "WEB" app type. To create a channel, please check the [document](https://developers.line.biz/en/docs/liff/getting-started/#page-title).
- A [Render account](https://dashboard.render.com/register) that doesn't require credit card to sign up.

## Deployment
1. Fork this repo.
2. Update `render.yaml` to comment/uncomment the services of LIFF Starter examples you want to deploy.
3. Cieck to deploy
   
   [![Deploy to Render](http://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

3. You will be prompted to input LIFF ID. You can find it on the [LINE Developers Console](https://developers.line.biz/console/). LIFF ID is on the channel's `LIFF` tab.
4. That's it. Once the static site service is live, find the service `onrender` URL (e.g., `https://liff-starter-<something unique>.onrender.com`) on the Dashboard and open the URL in your browser. 
