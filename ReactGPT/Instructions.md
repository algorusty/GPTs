# React Resources

[Learn](https://react.dev/learn)
[Reference](https://react.dev/reference/react)
[Community](https://react.dev/community)
[Blog](https://react.dev/blog)
[Releases](https://github.com/facebook/react/releases)
[Common Components](https://react.dev/reference/react-dom/components/common)

## [react@18.2.0](https://react.dev/reference/react)

- [Overview](https://react.dev/reference/react)
- **Hooks**
  - [use](https://react.dev/reference/react/use) - *Canary*
  - [useCallback](https://react.dev/reference/react/useCallback)
  - [useContext](https://react.dev/reference/react/useContext)
  - useDebugValue
  - useDeferredValue
  - useEffect
  - useId
  - useImperativeHandle
  - useInsertionEffect
  - useLayoutEffect
  - useMemo
  - useOptimistic - *Canary*
  - useReducer
  - useRef
  - useState
  - useSyncExternalStore
  - useTransition
- **Components**
  - [Fragment](https://react.dev/reference/react/Fragment)
  - Profiler
  - StrictMode
  - Suspense
- **APIs**
  - [cache](https://react.dev/reference/react/cache) - *Canary*
  - createContext
  - forwardRef
  - lazy
  - memo
  - startTransition
  - experimental_taintObjectReference - *Canary*
  - experimental_taintUniqueValue - *Canary*
- **Directives - Canary**
  - ['use client'](https://react.dev/reference/react/use-client)
  - ['use server'](https://react.dev/reference/react/use-server)

## [react-dom@18.2.0](https://react.dev/reference/react-dom)

- **Hooks**
  - [useFormState](https://react.dev/reference/react-dom/hooks/useFormState) - *Canary*
  - [useFormStatus](https://react.dev/reference/react-dom/hooks/useFormStatus) - *Canary*
- **Components**
  - [Common (e.g. div)](https://react.dev/reference/react-dom/components/common)
  - [form](https://react.dev/reference/react-dom/components/form) - *Canary*
  - input
  - option
  - progress
  - select
  - textarea
- **APIs**
  - [createPortal](https://react.dev/reference/react-dom/createPortal)
  - [flushSync](https://react.dev/reference/react-dom/flushSync)
  - findDOMNode
  - hydrate
  - render
  - unmountComponentAtNode
- **Client APIs**
  - [createRoot](https://react.dev/reference/react-dom/client/createRoot)
  - [hydrateRoot](https://react.dev/reference/react-dom/client/hydrateRoot)
- **Server APIs**
  - [renderToNodeStream](https://react.dev/reference/react-dom/server/renderToNodeStream)
  - [renderToPipeableStream](https://react.dev/reference/react-dom/server/renderToPipeableStream)
  - renderToReadableStream
  - renderToStaticMarkup
  - renderToStaticNodeStream
  - renderToString

## Legacy React APIs

- [Legacy React APIs](https://react.dev/reference/react/legacy)
  - [Children](https://react.dev/reference/react/Children)
  - cloneElement
  - Component
  - createElement
  - createFactory
  - createRef
  - isValidElement
  - PureComponent

[API Reference](https://react.dev/reference/react)

## Built-in React Hooks

Hooks allow using React features within components. They include state Hooks and others for various purposes.

- **State Hooks**
  - [useState](https://react.dev/reference/react/useState): Declares a state variable for direct updates.
  - [useReducer](https://react.dev/reference/react/useReducer): Declares a state variable with a reducer function for update logic.
  - More on state logic extraction: [Extracting State Logic into a Reducer](https://react.dev/learn/extracting-state-logic-into-a-reducer)

## Built-in React Components

React provides built-in components for efficient JSX usage.

- `<Fragment>`: Groups multiple JSX nodes.
- `<Profiler>`: Measures React tree rendering performance.
- `<Suspense>`: Shows fallback UI during child component loading.
- `<StrictMode>`: Enables additional development checks.

## Built-in React APIs

React exports APIs for defining components.

- `createContext`: Defines context for child components. Used with `useContext`.
- `forwardRef`: Exposes a DOM node as a ref to the parent. Used with `useRef`.
- `lazy`: Defers loading of a component’s code until first render.
- `memo`: Skips re-renders with same props. Used with `useMemo` and `useCallback`.
- `startTransition`: Marks state updates as non-urgent. Similar to `useTransition`.

## Directives in Canary

Directives for React Server Components or compatible libraries:

- `'use client'`: Marks code running on the client.
- `'use server'`: Marks server-side functions callable from client-side.

## React DOM Hooks (react-dom)

Hooks in `react-dom` for web applications:

- `useFormStatus`: Updates UI based on form status.
- `useFormState`: Manages state inside a form.

## React DOM Components

React supports all browser HTML and SVG components, including common and form components.

- **Common Components**: `<div>`, `<span>`, etc.
- **Form Components**: `<input>`, `<select>`, `<textarea>` - controlled with `value` prop.
- **All HTML Components**: From `<aside>` to `<wbr>`.
- **All SVG Components**: From `<a>` to `<view>`.

## React DOM APIs

Methods designed for web applications in `react-dom`:

- `createPortal`: Renders child components in a different DOM tree part.
- `flushSync`: Forces React to synchronously update the DOM.

## Client and Server APIs (react-dom)

- **Client APIs**: `createRoot` (creates a root in a DOM node), `hydrateRoot` (displays components in a node with server-generated HTML).
- **Server APIs for Node.js Streams**: `renderToPipeableStream`, `renderToStaticNodeStream`.
- **Server APIs for Web Streams**: `renderToReadableStream`.
- **Server APIs for Non-streaming Environments**: `renderToString`, `renderToStaticMarkup`.

## Deprecated React DOM APIs

Deprecated APIs in `react-dom`:

- `findDOMNode`: Finds a DOM node for a class component instance.
- `hydrate`: Mounts a tree from server HTML.
- `render`: Mounts a tree into the DOM.
- `unmountComponentAtNode`: Unmounts a tree from the DOM.

## Legacy APIs

Older APIs from the `react` package:

- `Children`: Manipulates JSX `children` prop.
- `cloneElement`: Creates a React element from another element.
- `Component`: Defines a React component as a class.
- `createElement`: Creates a React element, typically replaced by JSX.
- `createRef`: Creates a ref object.
- `isValidElement`: Checks if a value is a React element.
- `PureComponent`: Skips re-renders with same props.

## Deprecated Legacy API

- `createFactory`: Creates a function that produces React elements of a certain type.
