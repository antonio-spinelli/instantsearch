# react-instantsearch-hooks

React InstantSearch Hooks is an open-source UI library for React that lets you quickly build a search interface in your front-end application.

InstantSearch’s goal is to help you implement awesome search experiences as smoothly as possible by providing a [complete search ecosystem](https://algolia.com/doc/guides/getting-started/how-algolia-works/#the-full-ecosystem). InstantSearch tackles an important part of this vast goal by providing front-end primitives that you can assemble into unique search interfaces.

<p align="center">
  <a href="https://codesandbox.io/s/github/algolia/instantsearch.js/tree/master/examples/react-hooks/default-themes" title="Edit on CodeSandbox">
    <img alt="Edit on CodeSandbox" src="https://codesandbox.io/static/img/play-codesandbox.svg">
  </a>
</p>

> Note: `react-instantsearch-hooks` exports renderless components and hooks which can be used for both web and React Native. If you are using React in a web project, we recommend using the package `react-instantsearch-hooks-web` instead, as it includes complete components that render to the DOM.

## Installation

React InstantSearch Hooks is available on the npm registry. It relies on [`algoliasearch`](https://github.com/algolia/algoliasearch-client-javascript) to communicate with Algolia APIs.

```sh
yarn add algoliasearch react-instantsearch-hooks
# or
npm install algoliasearch react-instantsearch-hooks
```

## Getting started

React InstantSearch Hooks is a headless React library that lets you create an instant search results experience using Algolia’s search API.

Check out our [**Getting Started guide**](https://algolia.com/doc/guides/building-search-ui/getting-started/react-hooks/) to start implementing a full-featured search experience with React InstantSearch Hooks.

## API reference

Check out the [**API reference**](https://www.algolia.com/doc/api-reference/widgets/react-hooks/).

## Documentation

The documentation is available on [algolia.com/doc](https://algolia.com/doc/guides/building-search-ui/what-is-instantsearch/react-hooks/).

## Contributing

We welcome all contributors, from casual to regular 💙

- **Bug report**. Is something not working as expected? [Send a bug report][contributing-bugreport].
- **Feature request**. Would you like to add something to the library? [Send a feature request][contributing-featurerequest].
- **Documentation**. Did you find a typo in the doc? [Open an issue][contributing-newissue] and we'll take care of it.
- **Development**. If you don't know where to start, you can check the open issues that are [tagged easy][contributing-label-easy], the [bugs][contributing-label-bug] or [chores][contributing-label-chore].

To start contributing to code, you need to:

1.  [Fork the project](https://help.github.com/articles/fork-a-repo/)
1.  [Clone the repository](https://help.github.com/articles/cloning-a-repository/)
1.  Install the dependencies: `yarn`

Please read [our contribution process](https://github.com/algolia/instantsearch.js/blob/master/CONTRIBUTING.md) to learn more.

## License

React InstantSearch Hooks is [MIT licensed](../../LICENSE).

<!-- Links -->

[contributing-bugreport]: https://github.com/algolia/instantsearch.js/issues/new?template=BUG_REPORT.yml&labels=triage,Library%3A%20React+InstantSearch+Hooks
[contributing-featurerequest]: https://github.com/algolia/instantsearch.js/discussions/new?category=ideas&labels=triage,Library%3A%20React+InstantSearch+Hooks&title=Feature%20request%3A%20
[contributing-newissue]: https://github.com/algolia/instantsearch.js/issues/new?labels=triage,Library%3A%20React+InstantSearch+Hooks
[contributing-label-easy]: https://github.com/algolia/instantsearch.js/issues?q=is%3Aopen+is%3Aissue+label%3A%22Difficulty%3A+Easy%22+label%3A%22Library%3A%20React+InstantSearch+Hooks%22
[contributing-label-bug]: https://github.com/algolia/instantsearch.js/issues?q=is%3Aissue+is%3Aopen+label%3A%22Type%3A+Bug%22+label%3A%22Library%3A%20React+InstantSearch+Hooks%22
[contributing-label-chore]: https://github.com/algolia/instantsearch.js/issues?q=is%3Aissue+is%3Aopen+label%3A%22Type%3A+Chore%22+label%3A%22Library%3A%20React+InstantSearch+Hooks%22