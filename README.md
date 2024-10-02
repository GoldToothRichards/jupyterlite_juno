# JupyterLite Juno Demo

[![lite-badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://jll4e-saaaa-aaaal-aj2eq-cai.icp0.io/)



JupyterLite deployed to the [Internet Computer Blockchain](https://internetcomputer.org/) using [Juno](https://juno.build). 


A fork of the [JupyterLite Juno Demo](https://github.com/jupyterlite/jupyterlite-demo-juno) with some modifications to the `deploy.yml` workflow to deploy to the Internet Computer Blockchain using Juno.

## ✨ Try it in your browser ✨

➡️ **https://jll4e-saaaa-aaaal-aj2eq-cai.icp0.io/**

![github-pages](https://user-images.githubusercontent.com/591645/120649478-18258400-c47d-11eb-80e5-185e52ff2702.gif)

## Deploy your JupyterLite website on Juno

- Follow the instructions at https://juno.build/docs/add-juno-to-an-app/create-a-satellite to create your own satellite.
- Generate a new controller for your satellite from the juno console and add the token into the `JUNO_TOKEN` environment variable in your GitHub Actions secrets.
- Create your jupyter notebook and add it to the `content` folder.
- Push your changes to the main branch and your notebook will be deployed to the internet computer.

## Further Information

<img src="assets/juno_logo.svg" alt="Juno Logo" height="20">&nbsp;&nbsp;&nbsp;&nbsp; https://juno.build/docs/ 

<img src="assets/internet-computer-icp-logo.svg" alt="Juno Logo" height="20">&nbsp;&nbsp;&nbsp;&nbsp;  https://internetcomputer.org/docs/current/developer-docs/getting-started/overview-of-icp &nbsp;&nbsp;&nbsp;&nbsp;
