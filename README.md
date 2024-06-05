### Description
This is repo for jest bug XXX.  It shows that the `passWithNoTests` argument -- whether on the command line or in the config file -- does nothing when confronted with an empty file.

I believe the expected behavior should be that if the file is empty it is treated as having no tests.

### Running Instructions
1. Clone this repo
2. Run `npm i`
3. Execute one of the below commands using `npm run`

### NPM run commands (`npm run _____`)

|Name|Alias|
|----|-----------|
| `test:noargs` | `jest --verbose` |
| `test:cmd` | `jest --passWithNoTests --verbose` |
| `test:config` | `jest --config=jest.testconfig.js` |
| `test:showconfig` | `jest --config=jest.testconfig.js --showConfig` |
