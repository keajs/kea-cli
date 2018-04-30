# kea-cli

To get started with a new kea project, just type these commands:

Using npx, the npm package runner
```
npx kea-cli new my-project
cd my-project
npm install # or yarn
npm start   # or yarn start
```

or by installing kea-cli to your $PATH
```
npm install kea-cli -g 
kea new my-project
cd my-project
npm install # or yarn
npm start   # or yarn start
```

and open [http://localhost:2000/](http://localhost:2000/).

Later inside `my-project` run these to hack away:

```
kea g scene-name                               # new scene
kea g scene-name/component-name                # component under the scene
kea g scene-name/component-name/really-nested  # deeply nested logic
```

More documentation coming soon! Please help if you can!
