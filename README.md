services:
  - type: web
    runtime: node
    name: hidrourgencias
    buildCommand: npm install && npm run build
    startCommand: npm start
    # ...
    
