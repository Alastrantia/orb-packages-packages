# Package contribution guide
This guide will help you add a package to Orb and solarOS.

## Instructions
> Want to add your package? Follow this guide!

- Fork this repository
- Create a `.json` file in `/packages`
- Modify the `.json` file to fit your package, sample JSON below!
- Create a pull request on this repository
**You're done!**

## Sample JSON
This is an example JSON template you can use to add your package to Orb. Each package must have one mirror, and if you don't have one, point it to a GitHub repository branch!

```json
{
  "name": "Example",
  "author": "Example Author",
  "version": "1.0.0",
  "description": "Change this to your package's description",
  "mirrors": [
    "https://github.com/example/example",
    "https://anothermirror.com/example"
  ],
  "dependencies": [
    "https://example.com/dependency",
    "package-name-of-dependency-if-it-is-in-orb"
  ],
  "license": "MIT"
}
```