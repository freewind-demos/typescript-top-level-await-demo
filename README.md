TypeScript Top Level Await Demo
===========================

目前来说对于node/ts-node还是无解。

试遍各种办法都不行，包括这个： https://github.com/standard-things/esm/issues/580

要避免使用。

```
npm install
npm start
```

Note:

`esModuleInterop` is recommended to set to `true`,
since we can have consistent importing syntax with babel,
always use:

```
import some from 'some'
```

