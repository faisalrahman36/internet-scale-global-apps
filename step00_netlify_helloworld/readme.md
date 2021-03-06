[Install Node.js on Your Machine](https://nodejs.org/en/download/)

[Signup on Netlify](https://app.netlify.com/signup)

Install Globally:

npm install -g yarn

npm install -g netlify-cli 

[Watch this video](https://www.youtube.com/watch?v=RL_gtVZ_79Q&feature=youtu.be&t=812)

[Read this Document](https://cli.netlify.com/netlify-dev/)

Create project folder named "Step00_netlify_helloworld"

Change to project directory:

cd step00_netlify_helloworld

Create hello world index.html file in public folder in the poject directory.

You can also Start the Local Server:

netlify dev

Open in the Browser:

http://localhost:8888

Login to Netlify on Local Machine to start the publishing process:

netlify login

To publish on Netlify:

netlify deploy --prod

Notice that the tool has created .netlify directory in your project folder.

Now the site is published and you can copy the link given by the tool in the browser.

Add .gitignore so that .netlify directory not pushed to github

Bug: Currently there is some bug in the netlify dev tool, once the .netlify folder is created the dev tool stops working.

Alternatives to Netlify:

[Google Firebase](https://firebase.google.com/)

[Vercel](https://vercel.com/)

[Battle of the Jamstack platforms — Netlify, Vercel, AWS](https://www.lambrospetrou.com/articles/battle-of-jamstack-platforms-netlify-vercel-aws/)

Must Read:

[New to JAMstack? Everything You Need to Know to Get Started](https://snipcart.com/blog/jamstack)





