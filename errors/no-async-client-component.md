# No async client component

> Client components cannot be async functions.

#### Why This Error Occurred

As per the [React Server Component RFC on promise support](https://github.com/acdlite/rfcs/blob/first-class-promises/text/0000-first-class-support-for-promises.md), [client components cannot be async functions](https://github.com/acdlite/rfcs/blob/first-class-promises/text/0000-first-class-support-for-promises.md#why-cant-client-components-be-async-functions).

#### Possible Ways to Fix It

1. Remove the `async` keyword from the client component function declaration, or
2. Convert the client component to a server component
