<!--start-code-->

```js
/**
 * import data from
 * https://github.com/rsuite/rsuite/blob/main/docs/public/data/city-simplified.json
 */

const App = () => {
  return <CheckTree data={data} defaultExpandAll showIndentLine />;
};
ReactDOM.render(<App />);
```

<!--end-code-->