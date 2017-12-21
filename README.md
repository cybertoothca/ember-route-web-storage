# ember-route-web-storage

[![npm version](http://badge.fury.io/js/ember-route-web-storage.svg)](http://badge.fury.io/js/ember-route-web-storage) ![downloads](https://img.shields.io/npm/dy/ember-route-web-storage.svg) [![CircleCI](http://circleci.com/gh/cybertoothca/ember-route-web-storage.svg?style=shield)](http://circleci.com/gh/cybertoothca/ember-route-web-storage) [![Code Climate](http://codeclimate.com/github/cybertoothca/ember-route-web-storage/badges/gpa.svg)](http://codeclimate.com/github/cybertoothca/ember-route-web-storage) ![Dependencies](http://david-dm.org/cybertoothca/ember-route-web-storage.svg) [![ember-observer-badge](http://emberobserver.com/badges/ember-route-web-storage.svg)](http://emberobserver.com/addons/ember-route-web-storage) [![License](http://img.shields.io/npm/l/ember-route-web-storage.svg)](LICENSE.md)

## [DOCS](http://docs.ember-route-web-storage.cybertooth.io)

## [DEMO](http://docs.ember-route-web-storage.cybertooth.io/#hbs)

### Tested Against

[![ember-lts-2.4](https://img.shields.io/badge/ember--try-ember--lts--2.4-brightgreen.svg)](https://circleci.com/gh/cybertoothca/ember-route-web-storage)
[![ember-lts-2.8](https://img.shields.io/badge/ember--try-ember--lts--2.8-brightgreen.svg)](https://circleci.com/gh/cybertoothca/ember-route-web-storage)
[![ember-lts-2.12](https://img.shields.io/badge/ember--try-ember--lts--2.12-brightgreen.svg)](https://circleci.com/gh/cybertoothca/ember-route-web-storage)

[![ember-release](https://img.shields.io/badge/ember--try-ember--release-brightgreen.svg)](https://circleci.com/gh/cybertoothca/ember-route-web-storage)
[![ember-beta](https://img.shields.io/badge/ember--try-ember--beta-brightgreen.svg)](https://circleci.com/gh/cybertoothca/ember-route-web-storage)
[![ember-canary](https://img.shields.io/badge/ember--try-ember--canary-brightgreen.svg)](https://circleci.com/gh/cybertoothca/ember-route-web-storage)

# Collaboration Information

This README outlines the details of collaborating on this Ember add-on.

## Installation

* `git clone git@github.com:cybertoothca/ember-route-web-storage.git` this repository
* `cd ember-route-web-storage`


### With NPM

```
npm install
```

### With Yarn

```
yarn
```

## Running

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).

## Running Tests

* `npm test` (Runs `ember try:each` to test your addon against multiple Ember versions)
* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [https://ember-cli.com/](https://ember-cli.com/).

# Linking This Add-on For Local Testing

## Linking

1. From the command line at the root of __this__ project run the
`npm link` command to _link_ this add-on within your local
node repository.
1. From the _other_ Ember project that you wish to test this add-on
in, execute the following command:
`npm link ember-route-web-storage`.
1. Now in that same _other_ Ember project, you should go into the
`package.json` and add the ember add-on with the version _*_.  It will
look something like this: `"ember-route-web-storage": "*"`.  Now
when/if you execute `npm install` on this _other_ project it
will know to look for the linked add-on rather than fetch it from
the central repository.

## Unlinking

1. Remove the add-on from your local node repository with the following
command (that can be run anywhere):
`npm uninstall -g ember-route-web-storage`
1. Remove the reference to the `ember-route-web-storage`
in your _other_ project's `package.json`.
1. Run an `npm prune` and `bower prune` from the root of your _other_ project's command line.
