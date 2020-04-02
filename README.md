# Starter for typescript, tslint, mocha and chai

## typscript

`src` should keep all the source code

`build` will have all the typescript output file

[tsconfig](./tsconfig.json) has the typscript settings.

## tslint

`npm run lint` to execute code style check. 

`tslint --project .` is the underlying command.

[tslint.json](./tslint.json) is generate by command `tslint --init`

## mocha

`test` should keep all the mocha test script with file name patther `./**/*.spec.ts`

`npm run test` will execute mocha test. 

`mocha -r ts-node/register test/**/*.spec.ts` is the underlying command.


## How to use

To install dependency

`yarn install`

To run test

`npm run test`

To develop

`npm run start:dev`

To build

`npm run build`
