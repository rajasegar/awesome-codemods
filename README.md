# Awesome Codemods [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome codemod resources for various languages, libraries and frameworks

Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.


## Contents

- [JavaScript](#javascript)
- [ESNext](#esnext)
- [Typescript](#typescript)
- [Ruby](#ruby)
- [Frameworks](#frameworks)
- [Libraries](#libraries)
- [Organization specific Codemods](#organization-specific-codemods)
- [Editor Plugins](#editor-plugins)
- [Misc](#misc)
- [Awesome Lists](#awesome-lists)

## JavaScript
- [js-codemod](https://github.com/cpojer/js-codemod/) - Codemod scripts to transform code to next generation JS.
- [js-transforms](https://github.com/jhgg/js-transforms) - Some documented codemod experiments to help you learn.
- [coffee-to-es2015-codemod](https://github.com/Hacker0x01/coffee-to-es2015-codemod) - A set of JSCodeshift transforms that will help you transform your CoffeeScript codebase to ES2015.
- [5to6-codemod](https://github.com/5to6/5to6-codemod) - A collection of codemods that allow you to transform your js code from ES5 to ES6.
- [es5-function-to-class-codemod](https://github.com/dhruvdutt/es5-function-to-class-codemod) - Transform ES5 Functions to ES6 Classes.
- [webpack-babel-codemod](https://github.com/agirton/webpack-babel-codemod) - Convert anonymous webpack commonjs require statements to es2015 import statements.
- [rm-debugger](https://www.npmjs.com/package/rm-debugger) - Codemod for removing `debugger;`.
- [AMD Transformer](https://bitbucket.org/atlassian/amd-codemod/src) - Converts JS into AMDified JS (by Atlassian).
- [undecorate-codemod](https://github.com/tizmagik/undecorate-codemod) - Transformers experimental ESNext decorators syntax to simple currying.
- [jest-codemods](https://github.com/skovhus/jest-codemods) - Codemods for migrating to Jest .
- [refactoring-codemods](https://github.com/jurassix/refactoring-codemods) - Refactoring support for JavaScript via jscodeshift codemods.
- [sinon-codemod](https://github.com/hurrymaplelad/sinon-codemod) - Codemod scripts that update Sinon APIs .
- [codemod-imports-sort](https://github.com/bfncs/codemod-imports-sort) - Sort ES6 imports by type.
- [JamieMason/codemods](https://github.com/JamieMason/codemods) - A collection of transforms for use with JSCodeshift.
- [eslint-transforms](https://github.com/eslint/eslint-transforms) - Codemods for the ESLint ecosystem.
- [js-codemods](https://github.com/yangshun/js-codemods) - Some codemod scripts to transform code for good styling.
- [class-props-codemod](https://github.com/zertosh/class-props-codemod) - Transform old-style assigned static properties to class static properties.
- [flow-comments-codemod](https://github.com/escaton/flow-comments-codemod) - Convert flowtype syntax to valid JS.
- [async-await-codemod](https://github.com/sgilroy/async-await-codemod) - Codemod script for migrating promise-based functions to use async/await syntax.
- [sort-class-members-codemod](https://github.com/pastelsky/sort-class-members-codemod) - A codemod for automatically fixing issues reported by eslint-plugin-sort-class-members.
- [relative-to-alias](https://github.com/s-yadav/relative-to-alias) - A codemod to do large-scale refactor of your relative path imports to alias.
- [transform-imports](https://github.com/suchipi/transform-imports) - Tools that make it easy to codemod imports/requires in your JS.
- [expect-js-to-assert](https://github.com/twada/expect-js-to-assert) - A jscodeshift codemod that transforms from expect.js to Node assert.
- [optional-chaining-codemod](https://github.com/NullVoxPopuli/optional-chaining-codemod) 
- [chai-to-assert](https://github.com/twada/chai-to-assert) - A jscodeshift codemod that transforms from chai to Node assert.
- [nikgraf/js-codemod](https://github.com/nikgraf/js-codemod) - A collection of codemods.
- [amd-to-commonjs-codemod](https://github.com/skratchdot/amd-to-commonjs-codemod) - A codemod to transform amd style includes into commonjs includes.
- [js-codemod-import-absolute](https://github.com/bluedaniel/js-codemod-import-absolute) - Codemod to replace relative imports with absolute or custom paths.
- [relekang/codemods](https://github.com/relekang/codemods) 
- [jest-expect-codemod](https://github.com/devenbansod/jest-expect-codemod) - CodeMods for migrating `chai.assert`, `chai.expect`, `assert` -based test assertions to jest's `expect` assertions.
- [vasco3/cuadrante-codemods](https://github.com/vasco3/cuadrante-codemods) - Converts ES6 imports to commonJS requires.
- [immutablejs-eraser-codemod](https://github.com/mariosanchez/immutablejs-eraser-codemod) - A codemod to rescue you from a Immutable.js abuse.
- [underscore-to-native](https://github.com/zackargyle/codemods) - Underscore to native codemods.
- [chai-to-jasmine](https://github.com/AlexJuarez/chai-to-jasmine) - A chai to jasmine codemod that includes additional transforms for jest migration.
- [node-dep-codemod](https://github.com/joyeecheung/node-dep-codemod) - A collection of JSCodeshift codemod scripts for migrating code that uses deprecated Node.js APIs.
- [styletron/codemods](https://github.com/styletron/codemods) - Codemods for styletron.
- [rxjs-codemod](https://github.com/sergi/rxjs-codemod) - Codemod scripts to transform older RxJS code to RxJS5-compatible code.
- [cleaner-codemods](https://github.com/peoplenarthax/cleaner-codemods) - Simple codemods to destructure prop types.
- [apitsummit-codemods](https://github.com/perjansson/aptisummit-codemods) 
- [dsgkirkby/js-codemods](https://github.com/dsgkirkby/js-codemods) - Wrap switch statements in a code block.
- [EDITD/codemods](https://github.com/EDITD/codemods) - Radium to Glamour codemod.
- [bradencanderson/codemods](https://github.com/bradencanderson/codemods)
- [peakon/codemods](https://github.com/peakon/codemods) - I18n Context, Locale, No immutable class codemods.
- [knoopx/codemods](https://github.com/knoopx/codemods)
- [autobots](https://github.com/geekjuice/autobots) - Codemods for great good!.
- [ce-codemods](https://github.com/dogoku/ce-codemods) - Codemods for custom elements.
- [bseber/codemods](https://github.com/bseber/codemods) - Codemods for Jasmine refactoring.
- [strudel-codemod](https://github.com/strudeljs/strudel-codemod) - Strudel codemod scripts.
- [co-to-async](https://github.com/albinekb/co-to-async) - Take the step from co.wrap to async/await automagically.
- [DrewML/codemods](https://github.com/DrewML/codemods) 
- [skratchdot-codemods](https://github.com/skratchdot/skratchdot-codemods) - A collection of utility codemods.
- [aws-sdk-js-codemod](https://github.com/awslabs/aws-sdk-js-codemod) - Codemod scripts to update AWS SDK for JavaScript APIs.
- [codeshift-community](https://github.com/CodeshiftCommunity/CodeshiftCommunity) - Community-owned global registry and documentation hub for codemods. Write & run codemodes, share them with your friends.

## ESNext
- [5to6](https://github.com/jamischarles/5to6) - A collection of codemods that allow you to transform your js code from ES5 to ES6.
- [async-await-codemod](https://github.com/vivek12345/async-await-codemod) - Codemod to add try catch to all the async await statements.
- [codemod-get-to-optional-member-expression](https://github.com/eschaefer/codemod-get-to-optional-member-expressions) - Change Lodash `get` functions to ES7 optional member expressions.
- [idx-to-optional-chaining](https://github.com/cdlewis/idx-to-optional-chaining) - JSCodeShift codemod that transforms usage of idx to the draft optional chaining standard.
- [generator2async-codemod](https://github.com/shimohq/generator2async-codemod)
- [lebab-as-babel-plugins](https://github.com/rajatvijay/lebab-as-babel-plugins) - Codemod to transform ES5 code to ES6/7 and uses babel plugins.

## Typescript
- [ts-codemod](https://github.com/tusharmath/ts-codemod) - Typescript based codemods.
- [tscodeshift](https://github.com/KnisterPeter/tscodeshift) - A tscodeshift is a toolkit for running codemods over multiple TS files.
- [flowToTs](https://github.com/MarcoPolo/flowToTs) - Flow to Typescript codemods.
- [codemod-cli-ts](https://github.com/jmdejno/codemod-cli-ts) - CLI for generating codemods written in Typescript.
- [tsmod](https://github.com/WolkSoftware/tsmod) - Refactor TypScript code programmatically using codemods.
- [js-to-typescript-codemod](https://github.com/mattlewis92/js-to-typescript-codemod) - A simple codemod for helping migrate from babel to typescript. Converts default imports to wildcards.
- [riceburn](https://github.com/kenotron/riceburn) - A Typescript, JSON, and text file Code Mod Utility.
- [flowshift](https://github.com/albertywu/flowshift) - Flow to typescript codemods.
- [ts-codemod-scripts](https://github.com/buildo/ts-codemod-scripts) - Collection of basic JS/React codemod scripts to prepare for TS on a codebase.
- [type-import-codemod](https://github.com/IanVS/type-import-codemod) - Combine type and value imports using Typescript 4.5 type modifier syntax.
- [codemod-add-import-extensions](https://github.com/TrevorBurnham/codemod-add-import-extensions) - Add file extensions to imports to improve build performance and allow TypeScript code to be executed without compilation.

## Ruby
- [Ruby AST Explorer](https://github.com/rajasegar/ruby-ast-explorer) - AST Explorer for Ruby.
- [codeshift](https://github.com/rajasegar/codeshift) - JSCodeshift equivalent for Ruby.
- [cybertron](https://github.com/rajasegar/cybertron) - Codemod CLI to bootstrap Ruby codemods (transforms).
- [ruby_crystal_codemod](https://github.com/DocSpring/ruby_crystal_codemod) - A codemod / transpiler that can help you convert Ruby into Crystal.

## Frameworks

### React.js
- [react-codemod](https://github.com/reactjs/react-codemod) - React codemod scripts to update React APIs.
- [rackt-codemod](https://github.com/reactjs/rackt-codemod) - Codemod scripts for Rackt libraries.
- [ast-18n](https://github.com/sibelius/ast-i18n) - Easily migrate your existing React codebase to use i18n.
- [codemod-react-proptypes-to-flow](https://github.com/jamiebuilds/codemod-react-proptypes-to-flow)
- [proptypes-to-flow](https://github.com/mikhail-hatsilau/proptypes-to-flow-codemod) - Codemod to tranform react proptypes to flow.
- [react-hot-loader-codemod](https://github.com/sibelius/react-hot-loader-codemod) 
- [mst-codemod-to-0.10](https://github.com/mobxjs/mst-codemod-to-0.10) - A codemod to migrate to MobX-State-Tree 0.10 from previous versions.
- [babel-plugin-codemod-react-css-modules](https://github.com/Craga89/babel-plugin-codemod-react-css-modules) - Converts React components using imported CSS stylesheets to equivalent CSS Modules syntax.
- [metal-to-react](https://github.com/bryceosterhaus/metal-to-react) - Codemods for migrating metal-jsx to react.
- [rn-update-deprecated-modules](https://github.com/lucasbento/rn-update-deprecated-modules) - Codemod to update import declarations as per react-native > 0.59.x deprecations.
- [babel-plugin-hyperscript-to-jsx](https://github.com/RIP21/babel-plugin-hyperscript-to-jsx) - This plugin transforms react-hyperscript into JSX. Intended to be used as codemod.
- [cjsx-codemod](https://github.com/jsdf/cjsx-codemod) - A codemod for migrating off of coffee-react CJSX.
- [over_react_codemod](https://github.com/Workiva/over_react_codemod) - Codemods to help consumers of over_react automate the migration of UI component code.
- [yannvr/codemods](https://github.com/yannvr/codemods) - JS/React transforms because life is too short.
- [js2tsx](https://github.com/sjy/js2tsx) - A toolkit provide some codemod scripts based on jscodeshift to migrating react code base to typescript.
- [react-native-paper-codemod](https://github.com/callstack/react-native-paper-codemod)
- [react-codemod-pure-component-to-class](https://github.com/orzarchi/react-codemod-pure-component-to-class) - A react codemod to transform stateless/pure/functional components to class components.
- [denvned/codemod](https://github.com/denvned/codemod) - Relay Mutation - didResolveProps.
- [mukeshsoni/codemods](https://github.com/mukeshsoni/codemods) - Adds a data-test-id attribute to all jsx html elements.
- [js-react-codemods](https://github.com/nicholas-b-carter/js-react-codemods) - A boilerplate of JS 5/6/7 transforms for react/redux/js/etc.
- [react-with-hooks-removal-codemod](https://github.com/polizz/react-with-hooks-removal-codemod) - Remove the react-with-hooks library code when React 16.7.0 is released.
- [react-native-fix-inline-styles](https://github.com/ignacioola/react-native-fix-inline-styles) - Fix inline styles in react native components.
- [react-style-px-suffix-codemod](https://github.com/conorhastings/react-style-px-suffix-codemod) - Append px to shorthand values in style objects in react in prep for react 15 warning.


### Ember.js
- [ember-codemods](https://github.com/ember-codemods) - Official organization for Ember.js Codemods.
- [ember-watson](https://github.com/abuiles/ember-watson) - An Ember.js codemod to make upgrades automatic. 
- [test-selectors-codemod](https://github.com/lorcan/test-selectors-codemod) - A codemode for fixing the ember-test-selectors testSelector helper deprecation.
- [ember-i18n-to-intl-migrator](https://github.com/DockYard/ember-i18n-to-intl-migrator) - Migrate ember-i18n to ember-intl .
- [lil-codemods](https://github.com/jmdejno/lil-codemods) - Ember codemods.
- [jmdejno/ember-codemods](https://github.com/jmdejno/ember-codemods) - Ember code Transforms.
- [react-destructuring-assignment-codemod](https://github.com/thibaudcolas/react-destructuring-assignment-codemod) - A WIP jscodeshift codemod to destructure assignments of props, state, and context.
- [legacy-tests-codemod](https://github.com/patocallaghan/legacy-tests-codemod) - A collection of codemod's for legacy-tests-codemod.
- [ember-action-codemods](https://github.com/lennyburdette/ember-action-codemods) - Codemods for converting uses of action to the {{on}} modifier.
- [ember-k-codemod](https://github.com/cibernox/ember-k-codemod) - Removes all usages of Ember.K.
- [ember-computed-decorators-codemod](https://github.com/bwittenbrook3/ember-computed-decorators-codemod) - Codemod to update ember-computed-decorators to ember-decorators.
- [ember-cli-mirage-faker-codemod](https://github.com/caseywatts/ember-cli-mirage-faker-codemod) 
- [ember-component-jquery](https://github.com/patocallaghan/ember-component-jquery) - A codemod for migrating Ember Component code from `this.$()` to `$(this.element)`.

### Preact.js
- [preact-codemod](https://github.com/vutran/preact-codemod) - Shave some bytes by using Preact.

### Vue.js
- [vue-codemods](https://github.com/SergioCrisostomo/vue-codemods) - Collection of codemod scripts that help update and refactor Vue and JavaScript files.

### Angular.js
- [angular-codemods](https://github.com/arthurflachs/angular-codemods) - Codemods for refactoring legacy angular applications.

## Libraries

### Lodash
- [lodash-codemods](https://github.com/jfmengels/lodash-codemods) - Codemods to simplify upgrading Lodash versions.
- [lodash-to-lodash-amd-codemods](https://github.com/OliverJAsh/lodash-to-lodash-amd-codemods) - Lodash to [lodash-amd](https://github.com/lodash/lodash-amd) codemods.
- [optional-chaining-codemod](https://github.com/villesau/optional-chaining-codemod) - Codemod to migrate from Lodash get and logical and expressions to optional chaining.
- [js-transforms](https://github.com/gunar/js-transforms) - Codemod to replace lodash for lodash/fp.
- [modular-lodash-codemod](https://github.com/dgrijuela/modular-lodash-codemod) - Makes all your lodash imports modular.
- [kevinbarabash/codemods](https://github.com/kevinbarabash/codemods) - Lodash/Underscore to native.

### Mocha
- [mocha-to-jest-codemod](https://github.com/paularmstrong/mocha-to-jest-codemod) - Convert Mochan TDD with Chai assert tests to Jest.
- [mocha2ava-codemod](https://github.com/shimohq/mocha2ava-codemod) - A tranformer for migrating tests from Mocha to Ava.
- [ts-codemods](https://github.com/labarilem/ts-codemods) - Transformers for migrating callback-based Mocha tests to async/await based tests.

### AVA
- [jscodeshift-ava-tester](https://github.com/jfmengels/jscodeshift-ava-tester) - Codeshift wrapper to write smaller and better tests for your codemods using AVA.

### Styled Components
- [styled-components-codemods](https://github.com/styled-components/styled-components-codemods) - Automatic codemods to upgrade your styled-components code to newer versions.
- [styled-components-v3-to-v4-codemod](https://github.com/RIP21/styled-components-v3-to-v4-codemod) - Codemod to migrate deprecated .extend API in favor of only styled functions.

### react-router
- [react-router-v4-codemods](https://github.com/rajasegar/react-router-v4-codemods) - Codemods for migrating react-router from v3 to v4.
- [react-router-v6-codemods](https://github.com/rajasegar/react-router-v6-codemods) - Codemods for migrating react-router from v5 to v6.
- [@putout/plugin-react-router](https://github.com/coderaiser/putout/tree/master/packages/plugin-react-router) - Putout plugin adds ability to migrate to latest version of react router.

### material-ui
- [@mui/codemod](https://github.com/mui/material-ui/tree/master/packages/mui-codemod) - A collection of codemod scripts based for use with jscodeshift that help update MUI APIs.

### ant-design
- [codemod-v4](https://github.com/ant-design/codemod-v4) - Codemod cli for antd v4 upgrade.
- [antd-codemod](https://github.com/ant-design/antd-codemod) - Antd codemod scripts.
- [codemod-v5](https://github.com/ant-design/codemod-v5) - Codemod cli for antd v5 upgrade.

## Organization specific Codemods
This is the list of codemods used by a particular organization for their code transformations.
- [@freshworks/ember-codemods](https://github.com/freshdesk/ember-freshdesk-codemods) - A collection of codemods used in Freshworks.
- [shopify-codemod](https://github.com/shopify-graveyard/shopify-codemod) - A collection of Codemods written with JSCodeshift that will help update our old, crusty JavaScript to nice, clean JavaScript.
- [uber-codemods](https://github.com/uber-web/uber-codemods) - Because Code Changes and Evolves.
- [artsy/codemods](https://github.com/artsy/codemods) - Various codemods used around Artsy.
- [tune-codemods](https://github.com/TUNE-Archive/tune-codemods) - A collection of codemods we use at tune.
- [yapp-codemods](https://github.com/yappbox/yapp-codemods) - Yapp's codemods.
- [civicsource/codemod](https://github.com/civicsource/codemod/) 
- [salesforce/lwc-codemod](https://github.com/salesforce/lwc-codemod) - Codemods for Lightning Web Components.

## Editor Plugins
- [atom-codemod](https://github.com/rosswarren/atom-codemod) - Atom plugin for running codemods.
- [vscodemod](https://github.com/mikaelbr/vscodemod) - VSCode extension for doing codemod on selected text.
- [nmn/atom-codemod](https://github.com/nmn/atom-codemod) - Simple commands to apply specific Babel plugins/codemods on your code.

## Misc
- [ratchet](https://github.com/mskelton/ratchet) - Codemod to convert React PropTypes to TypeScript types.
- [flow-codemod](https://github.com/flowtype/flow-codemod) - Jscodeshift-powered mithril@0.2.x to mithril@1.x transformations .
- [mithril-codemods](https://github.com/MithrilJS/mithril-codemods)
- [webpack-codemods](https://github.com/okonet/webpack-codemods) - JS Codemod to automatically convert webpack config from v1 to v2.
- [js-codemods](https://github.com/entria/js-codemods) - Node.js/JavaScript codemods used at @entria.
- [jasmine-to-chai-codemod](https://github.com/vansosnin/jasmine-to-chai-codemod) - Codemod for jscodeshift to migrate your tests from Jasmine to Chai syntax.
- [closure-codemod](https://github.com/toshi-toma/closure-codemod) - Closure codemod scripts.
- [titanium-codemods](https://github.com/ewanharris/titanium-codemods) - Codemod scripts for Titanium Applications.
- [next-codemod](https://github.com/zeit/next-codemod) - Codemod transformations to help upgrade Next.js codebases.
- [date-fns-upgrade-codemod](https://github.com/date-fns/date-fns-upgrade-codemod) - Code mods for upgrading date-fns versions.
- [graphql2ts](https://github.com/sibelius/graphql2ts) - Transform .graphql to graphql-js typescript.
- [gen-codemod](https://github.com/noahsug/gen-codemod) - Generate codemods by specifying your starting -> desired JavaScript.
- [babel-plugin-localize](https://github.com/amerani/babel-plugin-localize) - Codemod to localize static strings.
- [generator-codemod](https://github.com/jamestalmage/generator-codemod) - A generator to create codemods quickly.
- [codemodes-tycoon](https://github.com/myshov/codemodes-tycoon) - Codemods from Tycoon.
- [pkg-upgrader](https://github.com/benmonro/pkg-upgrader) - Easily build codemod CLIs using jscodeshift. fork of lib-upgrader.
- [can-migrate](https://github.com/canjs/can-migrate) - CLI & codemod scripts for upgrading to CanJS 3, 4 and 5.
- [create-codemod-app](https://github.com/dangreenisrael/create-codemod-app) - Create Codemod App, a codemod generator and runner.
- [babel-plugin-glamorous-to-emotion](https://github.com/TejasQ/babel-plugin-glamorous-to-emotion) - A codemod to migrate existing React or Preact codebases from glamorous to emotion.
- [rxdart_codemod](https://github.com/brianegan/rxdart_codemod) - A collection of codemods to upgrade your RxDart code from one version to the next.
- [viewtools/codemods](https://github.com/viewstools/codemods) - Helpers to migrate your code to newer versions of Views Tools.
- [PHP-Codeshift](https://github.com/Atanamo/PHP-Codeshift) - A small PHP toolkit for running codemods (code transformations) over multiple PHP files.
- [gnome-shell-extension-es6-class-codemod](https://github.com/zhanghai/gnome-shell-extension-es6-class-codemod) - A jscodeshift transform that helps migrating GNOME Shell extensions to 3.32.
- [direct-import-codemod](https://github.com/limpbrains/direct-import-codemod) - Use direct imports to save JS bundle size.
- [d3-upgrade-codemods](https://github.com/expobrain/d3-upgrade-codemods) - Codemods to upgrade d3 from version 3.x.
- [generator-jscodeshif](https://github.com/scalvert/generator-jscodeshift) - A yeoman generator for a jscodeshift codemod.
- [tds-codemod](https://github.com/telus/tds-codemod) - TELUS Design System.
- [gsa-codeshift](https://github.com/bjoernricks/gsa-codeshift) - GSA codemod scripts.
- [bottender-codemod](https://github.com/bottenderjs/bottender-codemod) - Bottender codemod scripts.
- [mrm](https://github.com/sapegin/mrm) - Codemods for your project config files.
- [webdriverio/codemod](https://github.com/webdriverio/codemod) - A codemod to transform Protractor into WebdriverIO tests.
- [strapi/codemods](https://github.com/strapi/codemods) - CLI to help you migrate your Strapi applications & plugins from v3 to v4.
- [django-codemod](https://github.com/browniebroke/django-codemod) - A tool to automatically fix Django deprecations.


## Awesome Lists
- [awesome-ast](https://github.com/cowchimp/awesome-ast)
- [awesome-jscodeshift](https://github.com/sejoker/awesome-jscodeshift)
