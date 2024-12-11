# Helix Golf

[![Built with Starlight](https://astro.badg.es/v2/built-with-starlight/tiny.svg)](https://starlight.astro.build)

You can use the [Helix Editor](https://helix-editor.com/) to refactor code efficiently.

## Contributing

### Adding new examples

You can add new examples by editing the [`index.mdx`](https://github.com/NikitaRevenco/helix-golf/edit/main/src/content/docs/index.mdx) file.

To add an entry, copy-paste the following template:

````mdx
#### A descriptive title

An optional description.

##### Before

```js
input file
```

##### After

```
output file
```

##### Command

<details>

<summary>
`insert command here`
</summary>

1. Steps taken
1. To perform the
1. Transformation

</details>
````

### Running locally

1. Clone this repository
1. `pnpm install`
1. `pnpm dev`
