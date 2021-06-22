# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) SOFTWARE ENGINEERING IMMERSIVE

# Blog App

Your task is to build a blog using MongoDB, Mongoose, Express, and React

1. Create a repo named blog-app on github.com **not** on git.generalassemb.ly
2. Add your teammates as collaborators
3. Create a development branch
4. Add branch protection rules
5. Create each teammate's dev branch

Your app should include the following:

- CRUD on the backend (an api where you can create, read, update, and delete blog posts)
- CRUD on the frontend (a react frontend that has axios calls that can create, read, update, and delete blog posts)

Deploy!

### Start Here

```sh
npm init -y && 
npm install mongoose express morgan cors && 
npm install -D nodemon && 
echo "
/node_modules
.DS_Store
.env" >> .gitignore &&
mkdir db models seed routes controllers &&
touch server.js db/connection.js models/post.js seed/data.js routes/posts.js controllers/posts.js &&
code .
```
