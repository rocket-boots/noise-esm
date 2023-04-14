# Noise ESM
***Perlin and Simplex Noise in JavaScript, ESM (Module) format***

## Origins

This is a hard fork of the library from https://github.com/josephg/noisejs. The code is based on Stefan Gustavson's implementation. Do whatever you want with it.

## How to Use

```
npm install github:rocket-boots/noise-esm#v1.0.0
```

(or use any [tag](https://github.com/rocket-boots/noise-esm/tags) after the `#`)

The library exposes an object called noise with the following properties:

* `simplex2(x, y)`: 2D Simplex noise function
* `simplex3(x, y, z)`: 3D Simplex noise function
* `perlin2(x, y)`: 2D Perlin noise function
* `perlin3(x, y, z)`: 3D Perlin noise function
* `seed(val)`: Seed the noise functions. Only 65536 different seeds are supported. Use a float between 0 and 1 or an integer from 1 to 65536.

See example at https://github.com/josephg/noisejs

## To Do

- [ ] Separate functions into separate files if possible
- [ ] Allow functions to be imports separately
- [ ] Add examples
