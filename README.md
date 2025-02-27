## Getting Started

First, run the development server:

```bash
deno run dev

```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.




## Deploy on deno

edit nextjs config , set output to 'standlone'.

```js
const nextConfig: NextConfig = {
  output: "standalone",
};
```
**Using command line**

```bash
deno task build
deployctl deploy --include=.next --include=public jsr:@deno/nextjs-start/v15
```

