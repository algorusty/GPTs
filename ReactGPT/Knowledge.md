# react@18.2.0

[Learn](https://react.dev/learn)
[Reference](https://react.dev/reference/react)
[Community](https://react.dev/community)
[Blog](https://react.dev/blog)
[Releases](https://github.com/facebook/react/releases)

- [Overview](https://react.dev/reference/react)
- Hooks
  - [use](https://react.dev/reference/react/use) - This feature is available in the latest Canary
  - [useCallback](https://react.dev/reference/react/useCallback)
  - [useContext](https://react.dev/reference/react/useContext)
  - [useDebugValue](https://react.dev/reference/react/useDebugValue)
  - [useDeferredValue](https://react.dev/reference/react/useDeferredValue)
  - [useEffect](https://react.dev/reference/react/useEffect)
  - [useId](https://react.dev/reference/react/useId)
  - [useImperativeHandle](https://react.dev/reference/react/useImperativeHandle)
  - [useInsertionEffect](https://react.dev/reference/react/useInsertionEffect)
  - [useLayoutEffect](https://react.dev/reference/react/useLayoutEffect)
  - [useMemo](https://react.dev/reference/react/useMemo)
  - [useOptimistic](https://react.dev/reference/react/useOptimistic) - This feature is available in the latest Canary
  - [useReducer](https://react.dev/reference/react/useReducer)
  - [useRef](https://react.dev/reference/react/useRef)
  - [useState](https://react.dev/reference/react/useState)
  - [useSyncExternalStore](https://react.dev/reference/react/useSyncExternalStore)
  - [useTransition](https://react.dev/reference/react/useTransition)
- Components
  - [Fragment](https://react.dev/reference/react/Fragment)
  - [Profiler](https://react.dev/reference/react/Profiler)
  - [StrictMode](https://react.dev/reference/react/StrictMode)
  - [Suspense](https://react.dev/reference/react/Suspense)
- APIs
  - [cache](https://react.dev/reference/react/cache) - This feature is available in the latest Canary
  - [createContext](https://react.dev/reference/react/createContext)
  - [forwardRef](https://react.dev/reference/react/forwardRef)
  - [lazy](https://react.dev/reference/react/lazy)
  - [memo](https://react.dev/reference/react/memo)
  - [startTransition](https://react.dev/reference/react/startTransition)
  - [experimental_taintObjectReference](https://react.dev/reference/react/experimental_taintObjectReference) - This feature is available in the latest Canary
  - [experimental_taintUniqueValue](https://react.dev/reference/react/experimental_taintUniqueValue) - This feature is available in the latest Canary
- Directives - This feature is available in the latest Canary
  - ['use client'](https://react.dev/reference/react/use-client) - This feature is available in the latest Canary
  - ['use server'](https://react.dev/reference/react/use-server) - This feature is available in the latest Canary

## react-dom@18.2.0

- Hooks
  - [useFormState](https://react.dev/reference/react-dom/hooks/useFormState) - This feature is available in the latest Canary
  - [useFormStatus](https://react.dev/reference/react-dom/hooks/useFormStatus) - This feature is available in the latest Canary
- Components
  - [Common (e.g. div)](https://react.dev/reference/react-dom/components/common)
  - [form](https://react.dev/reference/react-dom/components/form) - This feature is available in the latest Canary
  - [input](https://react.dev/reference/react-dom/components/input)
  - [option](https://react.dev/reference/react-dom/components/option)
  - [progress](https://react.dev/reference/react-dom/components/progress)
  - [select](https://react.dev/reference/react-dom/components/select)
  - [textarea](https://react.dev/reference/react-dom/components/textarea)
- APIs
  - [createPortal](https://react.dev/reference/react-dom/createPortal)
  - [flushSync](https://react.dev/reference/react-dom/flushSync)
  - [findDOMNode](https://react.dev/reference/react-dom/findDOMNode)
  - [hydrate](https://react.dev/reference/react-dom/hydrate)
  - [render](https://react.dev/reference/react-dom/render)
  - [unmountComponentAtNode](https://react.dev/reference/react-dom/unmountComponentAtNode)
- Client APIs
  - [createRoot](https://react.dev/reference/react-dom/client/createRoot)
  - [hydrateRoot](https://react.dev/reference/react-dom/client/hydrateRoot)
- Server APIs
  - [renderToNodeStream](https://react.dev/reference/react-dom/server/renderToNodeStream)
  - [renderToPipeableStream](https://react.dev/reference/react-dom/server/renderToPipeableStream)
  - [renderToReadableStream](https://react.dev/reference/react-dom/server/renderToReadableStream)
  - [renderToStaticMarkup](https://react.dev/reference/react-dom/server/renderToStaticMarkup)
  - [renderToStaticNodeStream](https://react.dev/reference/react-dom/server/renderToStaticNodeStream)
  - [renderToString](https://react.dev/reference/react-dom/server/renderToString)

## Legacy React APIs

- [Legacy React APIs](https://react.dev/reference/react/legacy)
  - [Children](https://react.dev/reference/react/Children)
  - [cloneElement](https://react.dev/reference/react/cloneElement)
  - [Component](https://react.dev/reference/react/Component)
  - [createElement](https://react.dev/reference/react/createElement)
  - [createFactory](https://react.dev/reference/react/createFactory)
  - [createRef](https://react.dev/reference/react/createRef)
  - [isValidElement](https://react.dev/reference/react/isValidElement)
  - [PureComponent](https://react.dev/reference/react/PureComponent)

[API Reference](https://react.dev/reference/react)

Built-in React Hooks

Hooks let you use different React features from your components. You can either use the built-in Hooks or combine them to build your own. This page lists all built-in Hooks in React.

State Hooks

State lets a component “remember” information like user input. [For example, a form component can use state to store the input value, while an image gallery component can use state to store the selected image index.](https://react.dev/learn/state-a-components-memory)

To add state to a component, use one of these Hooks:

- [useState](https://react.dev/reference/react/useState) declares a state variable that you can update directly.
- [useReducer](https://react.dev/reference/react/useReducer) declares a state variable with the update logic inside a reducer function. [https://react.dev/learn/extracting-state-logic-into-a-reducer]

Built-in React Components

React exposes a few built-in components that you can use in your JSX.
Built-in components

    - `<Fragment>`, alternatively written as `<>...</>`, lets you group multiple JSX nodes together.
    - `<Profiler>` lets you measure rendering performance of a React tree programmatically.
    - `<Suspense>` lets you display a fallback while the child components are loading.
    - `<StrictMode>` enables extra development-only checks that help you find bugs early.

Your own components
You can also define your own components as JavaScript functions.

Built-in React APIs

In addition to Hooks and Components, the react package exports a few other APIs that are useful for defining components. This page lists all the remaining modern React APIs.

    - `createContext` lets you define and provide context to the child components. Used with `useContext`.
    - `forwardRef` lets your component expose a DOM node as a ref to the parent. Used with `useRef`.
    - `lazy` lets you defer loading a component’s code until it’s rendered for the first time.
    - `memo` lets your component skip re-renders with same props. Used with `useMemo` and `useCallback`.
    - `startTransition` lets you mark a state update as non-urgent. Similar to `useTransition`.

Directives
Canary

These directives are needed only if you’re using React Server Components or building a library compatible with them.

Directives provide instructions to bundlers compatible with React Server Components.
Source code directives

    - `'use client'` lets you mark what code runs on the client.
    - `'use server'` marks server-side functions that can be called from client-side code.

Built-in React DOM Hooks

The react-dom package contains Hooks that are only supported for web applications (which run in the browser DOM environment). These Hooks are not supported in non-browser environments like iOS, Android, or Windows applications. If you are looking for Hooks that are supported in web browsers and other environments see the React Hooks page. This page lists all the Hooks in the react-dom package.
Form Hooks
Canary

Form Hooks are currently only available in React’s canary and experimental channels. Learn more about React’s release channels here.

Forms let you create interactive controls for submitting information. To manage forms in your components, use one of these Hooks:

    `useFormStatus` allows you to make updates to the UI based on the status of the a form.
    `useFormState` allows you to manage state inside a form.


    function Form({ action }) {
        async function increment(n) {
            return n + 1;
        }
        const [count, incrementFormAction] = useFormState(increment, 0);
        return (
            <form action={action}>
                <button formAction={incrementFormAction}>Count: {count}</button>
                <Button />
            </form>
        );
    }

    function Button() {
        const { pending } = useFormStatus();
        return (
            <button disabled={pending} type="submit">
                Submit
            </button>
        );
    }

## React DOM Components

React supports all of the browser built-in HTML and SVG components.

## Common Components

All of the built-in browser components support some props and events.

- **Common components (e.g., `<div>`)**
  - This includes React-specific props like `ref` and `dangerouslySetInnerHTML`.

## Form Components

These built-in browser components accept user input:

- `<input>`
- `<select>`
- `<textarea>`

They are special in React because passing the `value` prop to them makes them controlled.

## All HTML Components

React supports all built-in browser HTML components. This includes:

- `<aside>`
- `<audio>`
- `<b>`
- `<base>`
- `<bdi>`
- `<bdo>`
- `<blockquote>`
- `<body>`
- `<br>`
- `<button>`
- `<canvas>`
- `<caption>`
- `<cite>`
- `<code>`
- `<col>`
- `<colgroup>`
- `<data>`
- `<datalist>`
- `<dd>`
- `<del>`
- `<details>`
- `<dfn>`
- `<dialog>`
- `<div>`
- `<dl>`
- `<dt>`
- `<em>`
- `<embed>`
- `<fieldset>`
- `<figcaption>`
- `<figure>`
- `<footer>`
- `<form>`
- `<h1>`
- `<head>`
- `<header>`
- `<hgroup>`
- `<hr>`
- `<html>`
- `<i>`
- `<iframe>`
- `<img>`
- `<input>`
- `<ins>`
- `<kbd>`
- `<label>`
- `<legend>`
- `<li>`
- `<link>`
- `<main>`
- `<map>`
- `<mark>`
- `<menu>`
- `<meta>`
- `<meter>`
- `<nav>`
- `<noscript>`
- `<object>`
- `<ol>`
- `<optgroup>`
- `<option>`
- `<output>`
- `<p>`
- `<picture>`
- `<pre>`
- `<progress>`
- `<q>`
- `<rp>`
- `<rt>`
- `<ruby>`
- `<s>`
- `<samp>`
- `<script>`
- `<section>`
- `<select>`
- `<slot>`
- `<small>`
- `<source>`
- `<span>`
- `<strong>`
- `<style>`
- `<sub>`
- `<summary>`
- `<sup>`
- `<table>`
- `<tbody>`
- `<td>`
- `<template>`
- `<textarea>`
- `<tfoot>`
- `<th>`
- `<thead>`
- `<time>`
- `<title>`
- `<tr>`
- `<track>`
- `<u>`
- `<ul>`
- `<var>`
- `<video>`
- `<wbr>`

> **Note**
>
> Similar to the DOM standard, React uses a camelCase convention for prop names. For example, you’ll write `tabIndex` instead of `tabindex`. You can convert existing HTML to JSX with an online converter.

## Custom HTML Elements

If you render a tag with a dash, like `<my-element>`, React will assume you want to render a custom HTML element. In React, rendering custom elements works differently from rendering built-in browser tags:

- All custom element props are serialized to strings and are always set using attributes.
- Custom elements accept `class` rather than `className`, and `for` rather than `htmlFor`.

If you render a built-in browser HTML element with an `is` attribute, it will also be treated as a custom element.

> **Note**
>
> A future version of React will include more comprehensive support for custom elements.
>
> You can try it by upgrading React packages to the most recent experimental version:
>
> - `react@experimental`
> - `react-dom@experimental`
>
> Experimental versions of React may contain bugs. Don’t use them in production.

## All SVG Components

React supports all built-in browser SVG components. This includes:

- `<a>`
- `<animate>`
- `<animateMotion>`
- `<animateTransform>`
- `<circle>`
- `<clipPath>`
- `<defs>`
- `<desc>`
- `<discard>`
- `<ellipse>`
- `<feBlend>`
- `<feColorMatrix>`
- `<feComponentTransfer>`
- `<feComposite>`
- `<feConvolveMatrix>`
- `<feDiffuseLighting>`
- `<feDisplacementMap>`
- `<feDistantLight>`
- `<feDropShadow>`
- `<feFlood>`
- `<feFuncA>`
- `<feFuncB>`
- `<feFuncG>`
- `<feFuncR>`
- `<feGaussianBlur>`
- `<feImage>`
- `<feMerge>`
- `<feMergeNode>`
- `<feMorphology>`
- `<feOffset>`
- `<fePointLight>`
- `<feSpecularLighting>`
- `<feSpotLight>`
- `<feTile>`
- `<feTurbulence>`
- `<filter>`
- `<foreignObject>`
- `<g>`
- `<hatch>`
- `<hatchpath>`
- `<image>`
- `<line>`
- `<linearGradient>`
- `<marker>`
- `<mask>`
- `<metadata>`
- `<mpath>`
- `<path>`
- `<pattern>`
- `<polygon>`
- `<polyline>`
- `<radialGradient>`
- `<rect>`
- `<script>`
- `<set>`
- `<stop>`
- `<style>`
- `<svg>`
- `<switch>`
- `<symbol>`
- `<text>`
- `<textPath>`
- `<title>`
- `<tspan>`
- `<use>`
- `<view>`

> **Note**
>
> Similar to the DOM standard, React uses a camelCase convention for prop names. For example, you’ll write `tabIndex` instead of `tabindex`. You can convert existing SVG to JSX with an online converter.
>
> Namespaced attributes also have to be written without the colon:
>
> - `xlink:actuate` becomes `xlinkActuate`.
> - `xlink:arcrole` becomes `xlinkArcrole`.
> - `xlink:href` becomes `xlinkHref`.
> - `xlink:role` becomes `xlinkRole`.
> - `xlink:show` becomes `xlinkShow`.
> - `xlink:title` becomes `xlinkTitle`.
> - `xlink:type` becomes `xlinkType`.
> - `xml:base` becomes `xmlBase`.
> - `xml:lang` becomes `xmlLang`.
> - `xml:space` becomes `xmlSpace`.
> - `xmlns:xlink` becomes `xmlnsXlink`.

## React DOM APIs

The `react-dom` package contains methods that are specifically designed for web applications, which run in the browser DOM environment. These methods are not supported for React Native.

## APIs

These APIs, which can be imported from your components, are rarely used but are available:

- `createPortal`: Allows you to render child components in a different part of the DOM tree.
- `flushSync`: Enables you to force React to flush a state update and update the DOM synchronously.

## Entry Points

The `react-dom` package provides two additional entry points:

- `react-dom/client`: Contains APIs to render React components on the client (in the browser).
- `react-dom/server`: Contains APIs to render React components on the server.

## Deprecated React DOM APIs

The following APIs will be removed in a future major version of React and are considered deprecated:

- `findDOMNode`: Finds the closest DOM node corresponding to a class component instance.
- `hydrate`: Mounts a tree into the DOM created from server HTML. Deprecated in favor of `hydrateRoot`.
- `render`: Mounts a tree into the DOM. Deprecated in favor of `createRoot`.
- `unmountComponentAtNode`: Unmounts a tree from the DOM. Deprecated in favor of `root.unmount()`.

## Client React DOM APIs

The `react-dom/client` APIs are designed to render React components on the client (in the browser). These APIs are generally used at the top level of your application to initialize your React tree. Often, a framework might call these APIs for you. Most of your components don't need to import or directly use these APIs.

## Client APIs

- `createRoot`: This API allows you to create a root to display React components inside a browser DOM node.
- `hydrateRoot`: It enables you to display React components inside a browser DOM node whose HTML content was previously generated by `react-dom/server`.

## Browser Support

React supports all popular browsers, including Internet Explorer 9 and above. However, some polyfills are required for older browsers such as IE 9 and IE 10.

## Server React DOM APIs

The `react-dom/server` APIs enable the rendering of React components to HTML on the server. These APIs are typically used only at the top level of your application to generate the initial HTML. Often, a framework might call these APIs for you. Most of your components don't need to import or directly use these APIs.

## Server APIs for Node.js Streams

These methods are available exclusively in environments that support Node.js Streams:

- `renderToPipeableStream`: Renders a React tree to a pipeable Node.js Stream.
- `renderToStaticNodeStream`: Renders a non-interactive React tree to a Node.js Readable Stream.

## Server APIs for Web Streams

These methods are available in environments with Web Streams, including browsers, Deno, and some modern edge runtimes:

- `renderToReadableStream`: Renders a React tree to a Readable Web Stream.

## Server APIs for Non-streaming Environments

These methods are suitable for environments that don’t support streams:

- `renderToString`: Renders a React tree to a string.
- `renderToStaticMarkup`: Renders a non-interactive React tree to a string.

Note that these non-streaming APIs offer limited functionality compared to the streaming APIs.

## Deprecated Server APIs

The following API is deprecated and will be removed in a future major version of React:

- `renderToNodeStream`: Renders a React tree to a Node.js Readable stream. (Deprecated)

## Legacy APIs

These APIs are exported from the `react` package, but their use in new code is generally not recommended. More modern or efficient alternatives are often available. See the linked individual API pages for suggested alternatives.

## General Legacy APIs

- `Children`: This API allows you to manipulate and transform the JSX received as the `children` prop.
- `cloneElement`: Enables you to create a React element using another element as a starting point.
- `Component`: Allows you to define a React component as a JavaScript class.
- `createElement`: Used to create a React element. Typically, JSX is used instead of this method.
- `createRef`: Creates a ref object which can contain an arbitrary value.
- `isValidElement`: Checks whether a value is a React element. This is typically used with `cloneElement`.
- `PureComponent`: Similar to `Component`, but it skips re-renders with the same props.

## Deprecated APIs

The following API is deprecated and will be removed in a future major version of React:

- `createFactory`: This API lets you create a function that produces React elements of a certain type.
