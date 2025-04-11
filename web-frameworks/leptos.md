# Leptos

- Rust framework attempting to replace the framework YEW by producing DOM instead of a virtual DOM, so rendering on the browser is much quicker.
    - Other arguments seem trivial...

## Build Options

1. Client-side rendering (CSR) use: **Trunk**
2. Full-stack, server-side rendering (SSR) use: **cargo-leptos**
      - Server-side rendering leads to slower developer iteration loop because you need to recompile both the server and client when making Rust code changes. 
      - But better load times for client and better SEO scores.
## Getting started

- https://book.leptos.dev/01_introduction.html
- https://book.leptos.dev/ssr/21_cargo_leptos.html
- https://book.leptos.dev/deployment/ssr.html


## Citations

- https://leptos.dev/