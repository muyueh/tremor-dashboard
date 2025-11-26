# Tremor – Dashboard

`Dashboard` is a SaaS application template from [Tremor](https://tremor.so). It's built
using [`Tremor Raw`](https://raw.tremor.so/docs/getting-started/installation)
and [Next.js](https://nextjs.org).

## Getting started

1. Install the dependencies. We recommend using pnpm. If you want to use `npm`,
   just replace `pnpm` with `npm`.

```bash
pnpm install
```

2. Then, start the development server:

```bash
pnpm run dev
```

3. Visit [http://localhost:3000](http://localhost:3000) in your browser to view
   the template.

## Deploying to GitHub Pages

This project is preconfigured for static export so it can be hosted on GitHub
Pages:

1. Build the static site. The `output: "export"` setting in
   [`next.config.mjs`](next.config.mjs) will place the files in the `out`
   directory.

   ```bash
   pnpm run build
   ```

2. Publish the contents of the `out` directory to the `gh-pages` branch (or your
   preferred Pages target). The base path defaults to `/tremor-dashboard` in
   production so links work correctly on GitHub Pages. If you publish under a
   different path, set `NEXT_PUBLIC_BASE_PATH` to that path (for example,
   `/my-custom-path`) before running the build.

## Notes

This project uses
[`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to
automatically optimize and load Inter, a custom Google Font.

This project uses
[`Tremor Raw`](https://raw.tremor.so/docs/getting-started/installation)
components for the UI.

## License

This site template is a commercial product and is licensed under the
[Tremor License](https://blocks.tremor.so/license).

## Learn more

For a deeper understanding of the technologies used in this template, check out
the resources listed below:

- [Tremor Raw](https://raw.tremor.so) - Tremor Raw documentation
- [Tailwind CSS](https://tailwindcss.com) - A utility-first CSS framework
- [Next.js](https://nextjs.org/docs) - Next.js documentation
- [Radix UI](https://www.radix-ui.com) - Radix UI Website
- [Recharts](https://recharts.org) - Recharts documentation and website
- [Tanstack](https://tanstack.com/table/latest) - TanStack table documentation
