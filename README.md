# openapi-sdd-template

This is a repository where I store the results of my trial and error in schema-driven development using Open API.

※ It is assumed that [bun](https://bun.sh/) is installed in your environment, so if bun is not available, please install [bun](https://bun.sh/) or replace the relevant parts with npm, yarn, etc.

## Getting Started

You don't have to think about anything difficult, just run the command below, so give it a try.

```
bun install
```

## Usage

### Export bundled OpenAPI file

All subsequent commands require a bundled OpenAPI file, so be sure to run this command first.

```
bun run openapi:bundle
```

### Export API specification static HTML file

```
bun run openapi:generate
```

### Export `schema.ts` file

```
bun run build-schema
```

### Start Mock Server

```
bun run mock-server
```

※ If you are in an environment where bun is not available, please replace the bunx command executed in the script property of `pakage.json` with the npx command.
