`babel index.js` succeeds and correctly strips flow types, but `babel-node index.js` borks. If `"type": "module"` is removed from package.json then both commands succeed.