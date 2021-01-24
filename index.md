function HelloMessage({ pudgy }) {
  return <div>Can I get an OWA OWA ?{pudgy}</div>;
}

ReactDOM.render(
  <HelloMessage pudgy="OWA OWA =)" />,
  document.getElementById('container')
);
