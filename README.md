# POWANET
POWANET – Global AI Network built for Pi ecosystem
{
  "version": 2,
  "builds": [{ "src": "next.config.js", "use": "@vercel/next" }],
  "routes": [{ "src": "/api/(.*)", "dest": "/api/$1" }]
}
