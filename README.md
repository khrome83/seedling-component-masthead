# seedling-component-masthead

A sample of how to share components with seedling.

1. Create a new file in `/components` with the name `Hero.ts`.

```ts
export default "https://raw.githubusercontent.com/use-seedling/seedling-component-masthead/master/index.html";
```

2. Use with seedling component directive.

```html
<:component use="Hero" />
```

**or**

```html
<Hero />
```

**Note** - All remote components require the `--allow-net` command line parameter for Deno.
