# Pericles
📱 Serverless text-to-vote application built with Node and Google Cloud Firestore.

## Installation

**Yarn**
```bash
$ yarn add pericles
```

**NPM**
```bash
$ npm i pericles
```

***

## Deployment

***

## FAQs

##### Firestore is in beta at the time of creation, why not use something more stable?

This repository is more or less refactoring some janky, old PHP & MySQL code I've used for years, so why not use the hot new thing ~~everyone~~ existing Cloud Datastore users are going to gripe about migrating to?

##### Unmet peer dependencies when running `yarn`?

This is due to a longstanding design decision by the Yarn maintainers. You can find other references to this behavior [in their issues](https://github.com/yarnpkg/yarn/issues/5347#issuecomment-376219812).

```bash
[3/4] 🔗  Linking dependencies...
warning "firebase-admin > @firebase/database@0.3.6" has unmet peer dependency "@firebase/app-types@0.x".
warning "firebase-admin > @firebase/database > @firebase/database-types@0.3.2" has unmet peer dependency "@firebase/app-types@0.x".
[4/4] 📃  Building fresh packages...
```
