# create-webp-webpack-plugin
Create `webp` image

## Install

```sh
npm i -D create-webp-webpack-plugin
// or
yarn add -D create-webp-webpack-plugin
```

## Options

#### match
Type: `regexp`
Default: `/\.(png|gif|svg)$/`

Match regexp that help plugin match the images need to transform to webp

#### webp
Type: `object`
Default: `{ lossless: true }`  

The options webp refer to [sharp webp options](https://sharp.pixelplumbing.com/api-output#webp)


## License

[MIT](http://opensource.org/licenses/MIT)
