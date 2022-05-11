# Hello VitePress

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

:tada: :100:

::: tip
This is a tip
:::

::: info
This is an info box
:::

::: warning
This is a warning
:::

::: danger
This is a dangerous warning
:::

::: details
This is a details block, which does not work in Internet Explorer or old versions of Edge.
:::

::: danger STOP
Danger zone, do not proceed
:::

::: details Click me to view the code

```js
console.log('Hello, VitePress!')
```

:::
<script setup>
import { useData } from 'vitepress'
const { page } = useData()
</script>

<pre>{{ page }}</pre>
