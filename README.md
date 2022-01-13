# imdf-typescript
Typescript definitions for IMDF based on OGC Standard, https://docs.ogc.org/cs/20-094/index.html

##Installation

```
# npm
npm install --save-dev imdf-typescript

# yarn
yarn add --dev imdf-typescript
```

Add `node_modules/imdf-typescript` to your `tsconfig.json`:

<!-- prettier-ignore -->
```json
{
  "compilerOptions": {
    "typeRoots": [
      "node_modules/imdf-typescript",
      "node_modules/@types"
    ]
  }
}
```

##Legal
IMDF is a community standard based on [RFC 7946](<https://tools.ietf.org/html/rfc7946>)