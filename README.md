# Gsoc 2023
---
layout: post
title: "GsoC 2023!"
date:   2023-06-01 02:00:36 +0530
categories: gsoc
tags: kde gsoc
---

![My Painting](https://i.postimg.cc/PrZMFFkc/Screenshot-2023-05-27-230629.png)




## About Me -

I am Utkarsh Kumar, currently pursuing a Bachelor of Technology (B.Tech) degree in Industries Management from the esteemed IIT Kharagpur. I am currently in my third year of study. I am pleased to announce that I have been selected for the prestigious Google Summer of Code program this year. During the program, my focus will be on enhancing the properties management of Digikam.

## Digikam Poperties Managment
Currently, users are endeavoring to modify images with a single click, such as altering image tags, author names, and the body text associated with the images. Consequently, I am actively engaged in devising a solution to address this issue. Primarily, my workflow revolves around the properties management of Digikam.</p>
    
## What it's all about
<div style="background-color:rgba(0, 0, 0, 0.0470588); padding:10px 10px;">
<p>
The majority of the images contain Exif data. In order to handle these images, it is necessary to extract all the metadata and store them in CSV files. To achieve this, a Python script is utilized to efficiently store a substantial amount of image metadata. Following this step, a command is executed to enable batch editing of the metadata, allowing for simultaneous modification of multiple images' metadata.
</p>
<p>
Digikam is an exceptional application that offers a multitude of advanced features, particularly in the realm of image editing. At present, my primary focus lies in exploring avenues to further enhance its capabilities, aiming to elevate the application to new levels of excellence.</p>
  
</p>
</div>

#### The new Bundle Creator 
Image editing preview
Images have metadata:

#_exif_ifd_pointer
#Tags
#Artist
#color_space
#body_serial_num

![W1](https://i.postimg.cc/90FtVLZY/image-1.jpg)

Adding <b>custom tags</b>The editing and modification of image metadata are of paramount importance, with the objective of accommodating user requirements effectively. The primary aim is to ensure a user-friendly experience, enabling users to effortlessly navigate through the process without encountering any challenges or obstacles.

### POST1 END







[![]()](https://app.netlify.com/start/deploy?repository=https://github.com/alchemyplatform/netlify-alchemy-dapp-boilerplates)

Visit the [](https://alchemy-cw3d-dapp-boilerplate.netlify.app/)


  [](https://docs.alchemy.com/docs/create-web3-dapp)
   [](https://github.com/alchemyplatform/create-web3-dapp) 
 [](https://createweb3dapp.alchemy.com) 
  [](https://createweb3dapp.alchemy.com/#templates) 
  [](https://createweb3dapp.alchemy.com/#components)
  [](https://github.com/alchemyplatform/create-web3-dapp-examples) 
   [](https://t.me/createweb3dapp) 

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
