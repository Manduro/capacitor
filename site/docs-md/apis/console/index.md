# Console

The Console API automatically sends `console.log` calls to the native log system on each respective platform. This enables, for example,
`console.log` calls to be rendered in the Xcode and Android Studio log windows.

Currently it's not possible to disable it, but that feature is coming.

## Example

```typescript
console.log('I really enjoy Avoacdo Toast, and I\'m not ashamed to admit it');
```

The string will show up in your Xcode or Android Studio log stream.