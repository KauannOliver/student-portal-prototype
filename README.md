# Student Portal Prototype

A responsive student-portal interface prototype with dashboard, course, calendar, document, finance, grade, and profile screens.


## Stack

Next.js, React, TypeScript, Tailwind CSS, and client-side local storage.

## Run locally

Requires Node.js and pnpm. Run `pnpm install`, then `pnpm dev`; open the local URL printed by Next.js. Use `pnpm build` to create a production build.

## Technical note

The current authentication state is browser-local and is not backed by a server identity provider or database. Do not enter real student or financial information.


## Snapshot review

This is a prototype interface, not an official university service or an affiliation claim. Institution branding in the current snapshot has been replaced with demonstration labels.

Git-triggered Vercel deployment is disabled in the included web configurations. This update publishes source and documentation only.

## License

Original application code is available under the [MIT license](LICENSE). Third-party libraries, models, fonts and bundled assets retain their own licenses.

## Dependency baseline

The original dependency manifest has peer conflicts. `npm install --legacy-peer-deps` is the compatibility install used for the snapshot checks; it does not resolve those upstream compatibility constraints. Dependency modernization remains a separate maintenance task. The inherited `next lint` script is incompatible with newer Next.js CLIs.

## Verification record

See [snapshot checks and remaining limitations](docs/VERIFICATION.md).
