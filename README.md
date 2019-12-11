# Awesome Codemods [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome codemod resources for various languages, libraries and frameworks

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.*

## Javascript
- [js-codemod](https://github.com/cpojer/js-codemod/) - Codemod scripts to transform code to next generation JS.
- [js-transforms](https://github.com/jhgg/js-transforms) - Some documented codemod experiments to help you learn.
- [coffee-to-es2015-codemod](https://github.com/Hacker0x01/coffee-to-es2015-codemod) - A set of JSCodeshift transforms that will help you transform your CoffeeScript codebase to ES2015
- [5to6-codemod](https://github.com/5to6/5to6-codemod) - A collection of codemods that allow you to transform your js code from ES5 to ES6.
- [es5-function-to-class-codemod](https://github.com/dhruvdutt/es5-function-to-class-codemod) - Transform ES5 Functions to ES6 Classes.
- [webpack-babel-codemod](https://github.com/agirton/webpack-babel-codemod) - Convert anonymous webpack commonjs require statements to es2015 import statements.
- [rm-debugger](https://www.npmjs.com/package/rm-debugger) - Codemod for removing `debugger;`
- [AMD Transformer](https://bitbucket.org/atlassian/amd-codemod/src) - converts JS into AMDified JS (by Atlassian)
- [undecorate-codemod](https://github.com/tizmagik/undecorate-codemod) - Transformers experimental ESNext decorators syntax to simple currying
- [jest-codemods](https://github.com/skovhus/jest-codemods) Codemods for migrating to Jest 
- [refactoring-codemods](https://github.com/jurassix/refactoring-codemods) Refactoring support for JavaScript via jscodeshift codemods
- [sinon-codemod](https://github.com/hurrymaplelad/sinon-codemod) Codemod scripts that update Sinon APIs 
- [codemod-imports-sort](https://github.com/bfncs/codemod-imports-sort) Sort ES6 imports by type 
- [JamieMason/codemods](https://github.com/JamieMason/codemods) A collection of transforms for use with JSCodeshift 
- [eslint-transforms](https://github.com/eslint/eslint-transforms) Codemods for the ESLint ecosystem 
- [js-codemods](https://github.com/yangshun/js-codemods) Some codemod scripts to transform code for good styling 
- [class-props-codemod](https://github.com/zertosh/class-props-codemod) Transform old-style assigned static properties to class static properties 
- [flow-comments-codemod](https://github.com/escaton/flow-comments-codemod) Convert flowtype syntax to valid JS
- [async-await-codemod](https://github.com/sgilroy/async-await-codemod) Codemod script for migrating promise-based functions to use async/await syntax
- [sort-class-members-codemod](https://github.com/pastelsky/sort-class-members-codemod) A codemod for automatically fixing issues reported by eslint-plugin-sort-class-members
- [relative-to-alias](https://github.com/s-yadav/relative-to-alias) 🛠️ A codemod to do large-scale refactor of your relative path imports to alias.
- [transform-imports](https://github.com/suchipi/transform-imports) Tools that make it easy to codemod imports/requires in your JS
- [expect-js-to-assert](https://github.com/twada/expect-js-to-assert) A jscodeshift codemod that transforms from expect.js to Node assert
- [generator2async-codemod](https://github.com/shimohq/generator2async-codemod)
- [optional-chaining-codemod](https://github.com/NullVoxPopuli/optional-chaining-codemod) 


## Typescript
- [ts-codemod](https://github.com/tusharmath/ts-codemod) Typescript based codemods
- [tscodeshift](https://github.com/KnisterPeter/tscodeshift) tscodeshift is a toolkit for running codemods over multiple TS files 
- [flowToTs](https://github.com/MarcoPolo/flowToTs) Flow to Typescript codemods
- [codemod-cli-ts](https://github.com/jmdejno/codemod-cli-ts) CLI for generating codemods written in Typescript.
- [tsmod](https://github.com/WolkSoftware/tsmod) Refactor TypScript code programmatically using codemods
- [js-to-typescript-codemod](https://github.com/mattlewis92/js-to-typescript-codemod) A simple codemod for helping migrate from babel to typescript. Converts default imports to wildcards.
- [riceburn](https://github.com/kenotron/riceburn) A Typescript, JSON, and text file Code Mod Utility
- [flowshift](https://github.com/albertywu/flowshift) flow to typescript codemods


## Frameworks

### React.js
- [react-codemod](https://github.com/reactjs/react-codemod) - React codemod scripts to update React APIs.
- [preact-codemod](https://github.com/vutran/preact-codemod) - Transform your React code to Preact.
- [rackt-codemod](https://github.com/reactjs/rackt-codemod) - Codemod scripts for Rackt libraries.
- [ast-18n](https://github.com/sibelius/ast-i18n) Easily migrate your existing React codebase to use i18n 
- [codemod-react-proptypes-to-flow](https://github.com/jamiebuilds/codemod-react-proptypes-to-flow)
- [react-hot-loader-codemod](https://github.com/sibelius/react-hot-loader-codemod) 
- [mst-codemod-to-0.10](https://github.com/mobxjs/mst-codemod-to-0.10) A codemod to migrate to MobX-State-Tree 0.10 from previous versions
- [babel-plugin-codemod-react-css-modules](https://github.com/Craga89/babel-plugin-codemod-react-css-modules) Converts React components using imported CSS stylesheets to equivalent CSS Modules syntax.
- [metal-to-react](https://github.com/bryceosterhaus/metal-to-react) Codemods for migrating metal-jsx to react
- [rn-update-deprecated-modules](https://github.com/lucasbento/rn-update-deprecated-modules) Codemod to update import declarations as per react-native > 0.59.x deprecations.
- [babel-plugin-hyperscript-to-jsx](https://github.com/RIP21/babel-plugin-hyperscript-to-jsx) This plugin transforms react-hyperscript into JSX. Intended to be used as codemod.
- [cjsx-codemod](https://github.com/jsdf/cjsx-codemod) A codemod for migrating off of coffee-react CJSX
- [over_react_codemod](https://github.com/Workiva/over_react_codemod) Codemods to help consumers of over_react automate the migration of UI component code.


### Ember.js
- [ember-codemods](https://github.com/ember-codemods) Official organization for Ember.js Codemods
- [ember-watson](https://github.com/abuiles/ember-watson) An Ember.js codemod to make upgrades automatic. 
- [test-selectors-codemod](https://github.com/lorcan/test-selectors-codemod) A codemode for fixing the ember-test-selectors testSelector helper deprecation
- [ember-i18n-to-intl-migrator](https://github.com/DockYard/ember-i18n-to-intl-migrator) Migrate ember-i18n to ember-intl 
- [lil-codemods](https://github.com/jmdejno/lil-codemods) Ember codemods
- [jmdejno/ember-codemods](https://github.com/jmdejno/ember-codemods) Ember code Transforms
- [react-destructuring-assignment-codemod](https://github.com/thibaudcolas/react-destructuring-assignment-codemod) A WIP jscodeshift codemod to destructure assignments of props, state, and context

### Preact.js
- [preact-codemod](https://github.com/vutran/preact-codemod) 🍧 Shave some bytes by using Preact.

### Vue.js
- [vue-codemods](https://github.com/SergioCrisostomo/vue-codemods) Collection of codemod scripts that help update and refactor Vue and JavaScript files.

## Libraries

### Lodash
- [lodash-codemods](https://github.com/jfmengels/lodash-codemods) Codemods to simplify upgrading Lodash versions 
- [lodash-to-lodash-amd-codemods](https://github.com/OliverJAsh/lodash-to-lodash-amd-codemods) - lodash to [lodash-amd](https://github.com/lodash/lodash-amd) codemods
- [optional-chaining-codemod](https://github.com/villesau/optional-chaining-codemod) Codemod to migrate from Lodash get and logical and expressions to optional chaining 

### Mocha
- [mocha-to-jest-codemod](https://github.com/paularmstrong/mocha-to-jest-codemod) Convert Mochan TDD with Chai assert tests to Jest
- [mocha2ava-codemod](https://github.com/shimohq/mocha2ava-codemod) - A tranformer for migrating tests from Mocha to Ava.

## AVA
- [jscodeshift-ava-tester](https://github.com/jfmengels/jscodeshift-ava-tester) codeshift wrapper to write smaller and better tests for your codemods using AVA


## Miscellaneous
- [antd-codemod](https://github.com/ant-design/antd-codemod) antd codemod scripts
- [styled-components-codemods](https://github.com/styled-components/styled-components-codemods) Automatic codemods to upgrade your styled-components code to newer versions.
- [flow-codemod](https://github.com/flowtype/flow-codemod) jscodeshift-powered mithril@0.2.x to mithril@1.x transformations 
- [mithril-codemods](https://github.com/MithrilJS/mithril-codemods)
- [shopify-codemod](https://github.com/shopify-graveyard/shopify-codemod) A collection of Codemods written with JSCodeshift that will help update our old, crusty JavaScript to nice, clean Javascript 
- [webpack-codemods](https://github.com/okonet/webpack-codemods) JS Codemod to automatically convert webpack config from v1 to v2
- [js-codemods](https://github.com/entria/js-codemods) Node.js/Javascript codemods used at @entria
- [uber-codemods](https://github.com/uber-web/uber-codemods) Because Code Changes and Evolves 
- [jasmine-to-chai-codemod](https://github.com/vansosnin/jasmine-to-chai-codemod) 🍵 Codemod for jscodeshift to migrate your tests from Jasmine to Chai syntax
- [artsy/codemods](https://github.com/artsy/codemods) Various codemods used around Artsy
- [closure-codemod](Closure codemod scripts)
- [titanium-codemods](https://github.com/ewanharris/titanium-codemods) Codemod scripts for Titanium Applications
- [next-codemod](https://github.com/zeit/next-codemod) codemod transformations to help upgrade Next.js codebases
- [vscodemod](https://github.com/mikaelbr/vscodemod) VSCode extension for doing codemod on selected text
- [date-fns-upgrade-codemod](https://github.com/date-fns/date-fns-upgrade-codemod) Code mods for upgrading date-fns versions
- [graphql2ts](https://github.com/sibelius/graphql2ts) Transform .graphql to graphql-js typescript
- [gen-codemod](https://github.com/noahsug/gen-codemod) Generate codemods by specifying your starting -> desired JavaScript.
- [ruby_crystal_codemod](https://github.com/DocSpring/ruby_crystal_codemod) A codemod / transpiler that can help you convert Ruby into Crystal
- [babel-plugin-localize](https://github.com/amerani/babel-plugin-localize) codemod to localize static strings
- [generator-codemod](https://github.com/jamestalmage/generator-codemod) A generator to create codemods quickly.
- [codemodes-tycoon](https://github.com/myshov/codemodes-tycoon) 


## Awesome Lists
- [awesome-ast](https://github.com/cowchimp/awesome-ast)
- [awesome-jscodeshift](https://github.com/sejoker/awesome-jscodeshift)
