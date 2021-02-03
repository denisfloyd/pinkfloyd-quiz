<p align="center">
   <img src="./.github/logo.png" alt="Happy" width="280"/>
</p>

<p align="center">	
   <a href="https://linkedin.com/in/denis-ladeira-814365115/">
      <img alt="Denis Mendonça Ladeira" src="https://img.shields.io/badge/-DenisLadeira-34bdeb?style=flat&logo=Linkedin&logoColor=white" />
   </a>
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/denismend/nlw03-happy?color=34bdeb">

  <a aria-label="Completed" href="https://nextlevelweek.com/episodios/omnistack/edicao/2">
    <img src="https://img.shields.io/badge/Happy-NLW 3.0-34bdeb?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAALVBMVEVHcExxWsF0XMJzXMJxWcFsUsD///9jRrzY0u6Xh9Gsn9n39fyMecy0qd2bjNJWBT0WAAAABHRSTlMA2Do606wF2QAAAGlJREFUGJVdj1cWwCAIBLEsRU3uf9xobDH8+GZwUYi8i6ucJwrxKE+7D0G9Q4vlYqtmCSjndr4CgCgzlyFgfKfKCVO0LrPKjmiqMxGXkJwNnXskqWG+1oSM+BSwD8f29YLNjvx/OQrn+g99oQSoNmt3PgAAAABJRU5ErkJggg=="></img>
  </a>
  <a href="https://github.com/denismend/nlw-02-proffy/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/denismend/nlw03-happy?color=34bdeb">
  </a> 
  <img alt="License" src="https://img.shields.io/badge/license-MIT-34bdeb">
</p>

<p align="center">
   :rocket: Project made to connect people in general and orphanages to visit, made in Next Level Week #3 @Rocketseat
</p>

<div align="center">
  <sub>The NLW #3 Proffy project. Built with ❤︎ by
    <a href="https://github.com/denismend">Denis Ladeira</a> and
    <a href="https://github.com/denismend/nlw03-happy/graphs/contributors">
      contributors
    </a>
  </sub>
</div>


<p align="center">
  <img src=".github/sample.gif">
</p>

# :pushpin: Table of Contents

* [Technologies](#computer-technologies)
* [Features](#rocket-features)
* [How to Run](#construction_worker-how-to-run)
* [Found a bug? Missing a specific feature?](#bug-issues)
* [Contributing](#tada-contributing)
* [License](#closed_book-license)

# :computer: Technologies
This project was made using the follow technologies:

* [Typescript](https://www.typescriptlang.org/)      
* [React](https://reactjs.org/)      
* [Expo](https://expo.io/)       
* [Express](https://expressjs.com/)      

# :rocket: Features

* Website to sign up teachers and students.
* App to connect teachers and students.

# :construction_worker: How to run
```bash
# Clone Repository
$ git clone https://github.com/denismend/nlw03-happy.git
```
### 📦 Run API

```bash
# Go to server folder
$ cd nlw03-happy/backend

# Install Dependencies
$ yarn install

# Run Aplication
$ yarn dev
```
Access API at http://localhost:3333/

### 💻 Run Web Project

```bash
# Go to web folder
$ cd nlw03-happy/web

# Install Dependencies
$ yarn install

# Run Aplication
$ yarn start
```
Go to http://localhost:3000/ to see the result.

### 📱 Run Mobile Project
To run the mobile project you need a cellphone with the app of [expo](https://play.google.com/store/apps/details?id=host.exp.exponent) instaled or a emulator android/ios.
<br />
After, fork this repository and clone to your machine. Inside of the project's folder run the following commands:

```bash
# Go to mobile folder
$ cd nlw03-happy/mobile

# Install Dependencies
$ yarn install

# Run Aplication
$ yarn start
```
Aferter read the QRCode with the app of [expo](https://play.google.com/store/apps/details?id=host.exp.exponent) or run on emulator.


# :bug: Issues

Feel free to **file a new issue** with a respective title and description on the the [Proffy](https://github.com/denismend/nlw03-happy/issues) repository. If you already found a solution to your problem, **i would love to review your pull request**!

# :tada: Contributing

There are many forms to contribute with the project, first of all you can give this github repo a Star.

If you want do help with the code follow the steps bellow

```ps
# Fork using GitHub official command line
# If you don't have the GitHub CLI, use the web site to do that.
$ gh repo fork denismend/nlw03-happy

# Clone your fork
$ git clone {your-fork-url}
$ cd proffy

# Create a branch with your feature
$ git checkout -b {branch-name}

# Make the commit with your changes
$ git commit -m 'Feat: {feature-name}'

# Send the code to your remote branch
$ git push origin {branch-name}
```

# :closed_book: License

Released in 2020 :closed_book: License

Made with love by [Denis Ladeira](https://github.com/denismend) 🚀.
This project is under the [MIT license](./LICENSE).


Give a ⭐️ if this project helped you!

# :ballot_box_with_check: To do list
** New features: https://www.notion.so/Vers-o-2-0-do-Happy-c754db7a4d41469e8c2d00fcf75392c4


# Example app with styled-components

This example features how you use a different styling solution than [styled-jsx](https://github.com/zeit/styled-jsx) that also supports universal styles. That means we can serve the required styles for the first render within the HTML and then load the rest in the client. In this case we are using [styled-components](https://github.com/styled-components/styled-components).

For this purpose we are extending the `<Document />` and injecting the server side rendered styles into the `<head>`, and also adding the `babel-plugin-styled-components` (which is required for server side rendering). Additionally we set up a global [theme](https://www.styled-components.com/docs/advanced#theming) for styled-components using NextJS custom [`<App>`](https://nextjs.org/docs/advanced-features/custom-app) component.

## Deploy your own

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel/next.js/tree/canary/examples/with-styled-components&project-name=with-styled-components&repository-name=with-styled-components)

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example with-styled-components with-styled-components-app
# or
yarn create next-app --example with-styled-components with-styled-components-app
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).

### Try it on CodeSandbox

[Open this example on CodeSandbox](https://codesandbox.io/s/github/vercel/next.js/tree/canary/examples/with-styled-components)

### Notes

When wrapping a [Link](https://nextjs.org/docs/api-reference/next/link) from `next/link` within a styled-component, the [as](https://styled-components.com/docs/api#as-polymorphic-prop) prop provided by `styled` will collide with the Link's `as` prop and cause styled-components to throw an `Invalid tag` error. To avoid this, you can either use the recommended [forwardedAs](https://styled-components.com/docs/api#forwardedas-prop) prop from styled-components or use a different named prop to pass to a `styled` Link.

<details>
<summary>Click to expand workaround example</summary>
<br />

**components/StyledLink.js**

```javascript
import Link from 'next/link'
import styled from 'styled-components'

const StyledLink = ({ as, children, className, href }) => (
  <Link href={href} as={as} passHref>
    <a className={className}>{children}</a>
  </Link>
)

export default styled(StyledLink)`
  color: #0075e0;
  text-decoration: none;
  transition: all 0.2s ease-in-out;

  &:hover {
    color: #40a9ff;
  }

  &:focus {
    color: #40a9ff;
    outline: none;
    border: 0;
  }
`
```

**pages/index.js**

```javascript
import StyledLink from '../components/StyledLink'

export default () => (
  <StyledLink href="/post/[pid]" forwardedAs="/post/abc">
    First post
  </StyledLink>
)
```

</details>
