# Albert_Park--Finmark

# Finmark by Bill Front-End Technical Evaluation

## Goals

This project is meant to only take 1-3 hours to complete. If our estimate seems
really off, please let us know!

This project will serve as the basis for discussion further in the hiring
process.

In `src/services` there are two JSON data files, `metadata.json` and
`entries.json`. Your job is to stitch those two data sets together and display
them. `src/services/index.js` contains two functions to get the data,
simulating an API response.

We've purposely left vague how the data should be displayed to the user.
Options could include a table, a series of cards, or something else! There
isn't a right answer.

### Requirements

- Dates should be formatted "MM-DD-YYYY" and currencies should be formatted
  according to the currency set in the drop down
- "Customer Name", "Partner Referral", and field with `null` values should not
  be displayed in the output
- Users should be able to optionally group deals by "Deal owner"
- Deals "won" should be emphasized
- Don't make changes to the `.json` files themselves; any changes to data
  structures should be done in code

## Project configuration

### Development server

This project template uses `create-react-app` under the hood, with some slight
modifications. To start the development server:

```bash
$ npm start
```

To run the unit tests (not a requirement):

```bash
$ npm test
```

### Type checking

Type checking for JS files is turned on by default. If this gets in your way,
you can disable it in the `tsconfig.json` file by deleting the line starting
with `checkJs`.

If you want to go all in and use Typescript, just convert the `.js(x)` files to
`.ts(x)`. Feel free to adjust the `tsconfig.json` file to your liking.

For Typescript, types written in JSDoc can be imported and used wherever you
need them.
