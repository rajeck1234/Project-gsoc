# Gsoc 2023
---
layout: post
title: "First Blog Post for GsoC 2023!"
date:   2023-05-15 02:00:36 +0530
categories: gsoc
tags: kde gsoc
---

![My Painting](https://i.postimg.cc/tCNW0GX5/groot4.jpg)

![Text](https://i.postimg.cc/HxkkRFkr/d4d5def6d88745cfb23d71a277770301.png)


## About Me - I am Groot.

I’m Srirupa Datta, about to finish my undergraduate Electrical Engineering degree at Jadavpur University, India, in June. This year, I got selected for Google Summer of Code and will be working on improving the Bundle Creator in Krita.

## My Introduction to Krita...

It's been more than a year since my last blogpost where I posted monthly updates on my progress on adding the Perspective Ellipse assistant tool in Krita during SoK'22. Being a painter who's interested in software development, I've been interested in Krita ever since I started using it.

## What it's all about
<div style="background-color:rgba(0, 0, 0, 0.0470588); padding:10px 10px;">
<p>
The primary format to share resources in Krita is a Resource Bundle, which is a compressed file containing all the resources together. It also contains some other information like metadata and a manifest so Krita can check there’s no errors in the file.
</p>
<p>
Krita’s Bundle Creator allows one to create their own bundle from the resources of their choice. The project that I would be working on, aims to improve the user interface of the current Bundle Creator, and allow the ability to edit bundles (which is currently not supported in Krita).
</p>
</div>

#### The new Bundle Creator 

The new Bundle Creator would look like an installation wizard with four pages which can be navigated using the `Next` and `Back` buttons, as well as buttons on the left side panel.

I think the primary objective behind designing the new Bundle Creator was to organize its workflow, that is, segregate sections devoted to a particular function or job. This is what led to the idea of using a wizard, instead of simple dialogs. Hence it would have four wizard pages:
- Choose Resources
- Choose Tags
- Enter Bundle Details
- Choose Save Location

Some of the cool features you can expect in the new Bundle Creator are a <b>gridview</b> like that of Resource Manager's to view all the resources, <b>filter resources</b> by name or tag before selecting, and an option to change back to the default listview from gridview if one wishes to stick to the previous layout.

![W1](https://i.postimg.cc/XNGbq9XG/Mod-W1-ss.png)

Adding <b>custom tags</b> to selected resources is a feature that we wish to integrate, but it would require a redesign of the `Choose Tags` wizard page that has been shown below. Just to clarify, these are all mockups! 

![W2](https://i.postimg.cc/sg3qYWfJ/mod-W2-ss.png)




Yet another important feature would be <b>reloading</b> last bundle data when opened/on startup - this is particularly useful when making a bundle for other people.

Apart from these, the new Bundle Creator would be <b>resizable</b>(Yaay!), and a separate Menu entry called Bundle Creator would be created. We plan to move `Manage Resource Libraries` , `Manage Resources` and `Bundle Creator` from `Menu > Settings` to `Menu > Resources`.

And lastly, I would be working on adding the feature of <b>editing bundles</b> - this however needs to be discussed more and would be dealt with post my mid term evaluations.


And of course, if you want to suggest some ideas or improvements, feel free to drop a comment on this [post](https://krita-artists.org/t/bundle-creator-improving-the-ui-ux-design/57405) I created on Krita Artists Forum!

This boilerplate is set up to be deployed on Netlify and you can directly deploy this project by clicking the button below:

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/alchemyplatform/netlify-alchemy-dapp-boilerplates)

Visit the [Live Demo here](https://alchemy-cw3d-dapp-boilerplate.netlify.app/)

## Resources
Please refer to CW3D's documentation and the following useful links for an in depth explanation of how to work with projects bootstrapped with CW3D:

-   [Docs](https://docs.alchemy.com/docs/create-web3-dapp) - Everything you need to know when using CW3D
-   [GitHub](https://github.com/alchemyplatform/create-web3-dapp) - look at the extensive code example or start contributing
-   [Website](https://createweb3dapp.alchemy.com) - Learn more about CW3D and add components to your project
-   [Templates](https://createweb3dapp.alchemy.com/#templates) - Check out the pre-built project templates
-   [Components Library](https://createweb3dapp.alchemy.com/#components) - Add features directly to your project through components
-   [Examples](https://github.com/alchemyplatform/create-web3-dapp-examples) - See the components implemented in a real world dapp
-   [Community](https://t.me/createweb3dapp) - Meet other builders, get support, and give feedback!

## Overview

This project serves as a boilerplate for creating decentralized applications (dApps) using [Create Web3 Dapp](https://github.com/alchemyplatform/create-web3-dapp). It is preconfigured to be deployed on [Netlify](https://www.netlify.com/), providing you with a seamless way to get your dApp up and running in no time.

This boilerplate is built using [CW3D (Create Web3 Dapp)](https://github.com/alchemyplatform/create-web3-dapp), a powerful tool developed by [Alchemy](https://www.alchemy.com/) that allows developers to rapidly create and deploy dApps.

## What's Included?

This boilerplate has everything you need to start building a dapp:

- Next.js
- Wagmi Hooks
- Ethers.js
- Rainbowkit
- Alchemy SDK

## Supported Chains

The project supports all the major EVM chains:

 - Ethereum
 - Polygon
 - Polygon zkEVM
 - Arbitrum
 - Optimism

## Getting Started

### Prerequisites

To get started with this boilerplate, you'll need to have the following software installed on your local machine:

- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)

### Installation

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/alchemyplatform/netlify-alchemy-dapp-boilerplates.git
   ```
2. Navigate to the project directory:
   ```
   cd netlify-alchemy-dapp-boilerplates
   ```
3. Install the required dependencies:
   ```
   yarn install
   ```

### Running the Project

1. Start the local development server:
   ```
   yarn run dev
   ```
2. Open your browser and navigate to [`http://localhost:3000/`](http://localhost:3000/) to view the dApp in action.

### Deploying to Netlify

This boilerplate is set up to be deployed on Netlify and you can directly deploy this project by clicking the button below:

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/alchemyplatform/netlify-alchemy-dapp-boilerplates)

 If you prefer to deploy it manually, you can follow these steps:

1. Sign up for a Netlify account at [netlify.com](https://www.netlify.com/) if you don't already have one.
2. Install the Netlify CLI:
   ```
   npm install -g netlify-cli
   ```
3. Run the following command to deploy your dApp to Netlify:
   ```
   netlify deploy
   ```
4. Follow the prompts and provide the required information. Your dApp will be deployed and accessible via a unique URL.

## Project Structure

The boilerplate project is a Next.js application with the following structure:

```
📦root
 ┣ 📂components
 ┃ ┣ 📂navigation
 ┃ ┃ ┗ 📜navbar.jsx
 ┃ ┗ 📜InstructionsComponent.jsx
 ┣ 📂layout
 ┃ ┗ 📜mainLayout.jsx
 ┣ 📂pages
 ┃ ┣ 📜_app.js
 ┃ ┗ 📜index.jsx
 ┣ 📂public
 ┃ ┗ 📜cw3d-logo.png
 ┣ 📂styles
 ┃ ┣ 📜Home.module.css
 ┃ ┣ 📜InstructionsComponent.module.css
 ┃ ┣ 📜Navbar.module.css
 ┃ ┗ 📜globals.css
 ┣ 📜.gitignore
 ┣ 📜README.md
 ┣ 📜next.config.js
 ┣ 📜package-lock.json
 ┗ 📜package.json
```

Start editing the `pages/index.jsx` file to customize the project according to your own needs!
