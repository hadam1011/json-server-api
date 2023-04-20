{
  "version": 2,
  "builds": [
    {
      "src": "json-server --watch db.json --port $PORT",
      "use": "@vercel/node"
    }
  ],
  "routes": [
    {
      "src": "/(.*)",
      "dest": "/"
    }
  ]
}
