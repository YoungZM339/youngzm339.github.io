# YoungZM339 Homepage

Personal homepage and frontend source for [youngzm.com](https://youngzm.com).

## What this repository contains

This repository contains the source files used to build and publish the personal homepage. Treat the generated output as a build artifact and keep source content, configuration, and deployment settings documented separately.

## Local development

1. Inspect package.json to confirm the supported Node.js version and available scripts.
2. Install dependencies with the package manager selected by the lockfile.
3. Run the development script listed by package.json.
4. Build the production output before publishing.

~~~bash
npm install
npm run
~~~

## Deployment checklist

- Keep secrets and personal tokens outside the repository.
- Verify links, mobile layout, metadata, and accessibility before publishing.
- Configure the custom domain and HTTPS in the hosting provider.
- Do not commit generated caches or local environment files.

## License

Unless a subdirectory states otherwise, the source is maintained as a personal project. Check the repository history and existing license files before reusing assets.