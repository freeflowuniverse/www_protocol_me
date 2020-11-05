# protocol-website
This will be the Gridsome environment used for generating the protocol.me website. 

## Installation

### Install Gridsome
Gridsome is the environment that builds this project. If you haven't installed Gridsome yet you can install it with [this link](https://gridsome.org/docs/#how-to-install).

[Yes, I need to install gridsome](https://gridsome.org/docs/#how-to-install)

### Install Protocol.me environment locally
After installing `gridsome` and `cloning the project` you can build **a local server with the protocol.me site running** with this command:

```gridsome develop```

_Note: Make sure you are in the main directory when running this command._

### Build a static html website 
To build a static html website you can run this command in the terminal:

```gridsome build```

_Note: Make sure you are in the main directory when running this command._

After building the static html website is in the `/dist` folder.

---

## Writing content
All the content is written under the `/content/docs/` folder. Every page has it's own folder to organize images and other content.

- It is under the direcory [content/docs](content/docs)
- All files are markdown (.md) format

## Editing

- Always use `-` instead of `_` in naming files and directories 
- Create a new folder for each item you want to add to `protocol.me` with the naming convention in the previous point
- inside each directory put
    - `index.md` contains markdown
    - `/img` directory with images for that item
- referring to img `crystaltwin.png` from `index.md` of `crystaltwin` item can be done simpy by `![](./img/crystaltwin.png)`
- **Editing md files**

  - All files start with this piece of code, this is meant to control navigation into different sections defined in the sidebar menu.

    ```
    ---
    description: ''
    sidebar: 'docs'
    prev: '/docs/root-objects/'
    next: '/docs/frequently-asked-questions'
    ---


## You want to go deeper ?

Read more [on the original docc site](https://docc-theme.netlify.app)


## Create new project using `threefold gridsome-docc` 

Run `gridsome create app https://github.com/threefoldfoundation/gridsome-docc`
