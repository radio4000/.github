# [radio4000](https://radio4000.com) (`r4`)

This github organisation is the new `alpha` version of `r4` (migrating to supabase from firebase).

The new architecture is currently as follow:

- [radio4000/cms-astro](https://github.com/radio4000/cms-astro), the `cms`, now made with `astro`; to organize the components in routes
- [radio4000/sdk](https://github.com/radio4000/sdk), [npm](https://www.npmjs.com/package/@radio4000/sdk) module, javascript sdk
- [radio4000/components](https://github.com/radio4000/components) [npm](https://www.npmjs.com/package/radio4000-player), web components, for the UI and using the sdk
- [radio4000/supabase](https://github.com/radio4000/supabase), the backend, internal APIs, databases

## To be migrated

- [internet4000/radio4000-player](https://github.com/internet4000/radio4000-player), currently relying on firebase
- [radio4000/api](https://github.com/radio4000/api), currently relying on firebase
