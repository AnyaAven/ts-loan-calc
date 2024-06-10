1. Do we need html script to have .js or ts extension?
    - .ts in the html

    FIX: The html file also was also called calculator.html
        - Should be index.html for vite to work correctly

    Used: vite --open to start

    converted the script file to module
``` html
<script type="module">
    import { start } from "./calculator.ts";
    start();
</script>

```

2. why do we have semicolons in our type?
    Because *shrug* that's how it is
    - Why would , and ; work?
     Either works

## learning

Format

``` ts
function ({ amount, years, rate }: {
    amount: number,
    years: number,
    rate: number,
  }): number {
    // CODE HERE
  }
```

Don't do TS's job if it can do it for you!

(evt: SubmitEvent) vs only (evt)

The second one is better! TS knows the evt, typically!

