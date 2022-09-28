# google-drive-react-tutorial

# Create a Google Drive clone with MongoDB, Express, NodeJS, and React.

In this guided learning tutorial we are going to make a **Google Drive clone** using ReactJS. We will be also using **firebase** to store the files and for authentication.

We will be using **styled components** to style our project. 

We need to first create a new project with create-react-app called google drive from terminal.

## Create New Project

`cd desktop`

`npx create-react-app google-drive`
`cd google-drive`

IMAGE 9

## Run The Project

Run the project with `npm start` and it will look like below.

IMAGE 10

___


After the project is created, we will delete some of the boiler plate files.

IMAGE 3

Next, in `index.js` file we will delete the not required code and it will look like below.

IMAGE 4

Next, `App.js` file we will delete the not required code and it will look like below.

IMAGE 5

We will make all `margin` to `0` in the `index.css` file.

IMAGE 6

The Output Now Looks Like This

IMAGE 11


## Create Components

Next, create a `components` folder inside `src` folder. And in it create a `Header.js` file. 

`mkdir src/components`

`touch src/components/Header.js`

In the `App.js` file, we will include it.

IMAGE 12

Now, in the `Header.js` file we will add the below styled components. We have also installed the package of `styled-components` in the integrated terminal.

IMAGE 13

Now, we will use the created Styled components and also show a image using `img` tag in the `Header.js` file.








