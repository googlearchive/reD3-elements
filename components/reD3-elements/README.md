reD3-elements
=============

See the [component page](http://polymerlabs.github.io/reD3-elements) for more information.

reD3-import
===========

Import files are a new invention, so libraries like [`reD3`](http://bugzu.github.io/reD3/) do not yet provide them.

`reD3-import` is an intermediary that provides an import file for the `reD3` component.
`reD3-import` depends on `reD3`.

Components that want to use `reD3` should depend on `reD3-elements` and import `reD3-import` to be safe from library duplication. 
Such components need not use Polymer or `reD3-elements`, but we put the import and the element in one package for convenience.
