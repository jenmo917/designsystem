Flere tabs kan grupperes i en `TabGroup`:

```js
const Tab = require('./Tab').default;

<TabGroup>
    <Tab>Dette er en tab</Tab>
    <Tab selected={true}>Dette er en valgt tab</Tab>
    <Tab>Dette er en annen tab</Tab>
</TabGroup>;
```

Det finnes også en tynnere variant ved bruk av `thin`:

```js
const Tab = require('./Tab').default;

<TabGroup thin={true}>
    <Tab>Dette er en tab</Tab>
    <Tab selected={true}>Dette er en valgt tab</Tab>
    <Tab>Dette er en annen tab</Tab>
</TabGroup>;
```
