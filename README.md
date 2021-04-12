# Deploy `json-graphql-server` to `{{ free hosting site }}`

## Configuration

Create your configuration file (copy `.env.sample` to `.env`) to specify application port (3000 by default).

---

## Deploy to custom server

Install node process manager PM2: `npm i -g pm2`.

And run:
`pm2 start npm --name "app name" -- start`

