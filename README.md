# story-book-vite-object-object-issue
To reproduce this bug:   
1) run `npm i`   
2) `npm run build-storybook`   
3) Serve storybook production somewhere, you can use https://www.npmjs.com/package/http-server install it globally then navigate to this project root and run `http-server storybook-static`   
4) Open storybook production in browser and go to button docs
5) Click "Show Code" first time, observe "Object object" instead of component code, if you close preview and click "Show Code" second time this will work properly   

Note: It is not reproducible on localhost with `npm run storybook`