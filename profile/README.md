# [Radio4000](https://radio4000.com) [ r4000, r4k, r4 ]

This github organisation is the new `prototype` version of radio4000 systems (backend migration to supabase from firebase).

> All welcome to ask any question or chat on [#radio4000:matrix.org](https://matrix.to/#/#radio4000:matrix.org); visit [github/internet4000](https://github.com/internet4000) for other projects and previous r4 versions

The new architecture of repositories is currently, from top to bottom in the stack:

## Sites

- [beta](https://github.com/radio4000/radio4000.github.io) → [beta.radio4000.com](https://beta.radio4000.com/), the cms, using the `<r4-app>` component. Will become the new radio4000.com. Has all the features. 
- [profiles](https://github.com/radio4000/profiles) → [4000.network](https://4000.radio), used for showing single radios on subdomains, example https://918.4000.radio
- [migrate tool](https://github.com/radio4000/migrate-tool) → [migrate.radio4000.com](https://migrate.radio4000.com), an app for migrating a radio and tracks from old R4 to new R4

## Packages

- [@radio4000/components](https://github.com/radio4000/components) → [npm](https://www.npmjs.com/package/@radio4000/components) & [components.radio4000.com](https://components.radio4000.com),  a set of web components, used to create reusable UI (it uses the SDK)
- [@radio4000/sdk](https://github.com/radio4000/sdk) → [npm](https://www.npmjs.com/package/@radio4000/sdk), [documentation](https://sdk.radio4000.com/docs)  a JavaScript Software Development Kit, to have all necessary functions to communicate with R4
- [radio4000-player](https://github.com/internet4000/radio4000-player) → [npm](https://www.npmjs.com/package/radio4000-player), [site](https://player.radio4000.com), a web component, legacy currently relying on Firebase

## Backend 

- [radio4000/api](https://github.com/radio4000/api) → https://api.radio4000.com, currently relying on firebase
- [radio4000/supabase](https://github.com/radio4000/supabase) → the new backend (it uses [supabase](https://supabase.com), which provides us with database, authentication, internal APIs, edge functions, realtime subscriptions, and storage
- firebase → our original database, still in use on radio4000.com. To be deprecated

