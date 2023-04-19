This is a [Tina CMS](https://tina.io/) project.

## Local Development

Install the project's dependencies:

```
yarn install
```

Run the project locally:

```
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Building the Starter Locally (Using the hosted content API)

Replace the `.env.example`, with `.env`

```
NEXT_PUBLIC_TINA_CLIENT_ID=<get this from the project you create at app.tina.io>
TINA_TOKEN=<get this from the project you create at app.tina.io>
NEXT_PUBLIC_TINA_BRANCH=<Specify the branch with Tina configured>
```

Build the project:

```bash
yarn build
```

## Learn More

This repo is based on Tina CMS's bare bones example.