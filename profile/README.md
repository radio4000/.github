# [radio4000](https://radio4000.com) [ r4000, r4k, r4 ]

This github organisation is the new `prototype` version of radio4000 systems (backend migration to supabase from firebase).

The new architecture of repositories is currently, from top to bottom in the stack:

- [app](https://github.com/radio4000/radio4000.github.io) { [site](https://beta.radio4000.com/) } the `cms`, using the `<r4-app>` component. Will become the new radio4000.com
- [components](https://github.com/radio4000/components) { [npm](https://www.npmjs.com/package/@radio4000/components), [site](https://radio4000.github.io/components) } a set of web-components, used to create reusable UI (it uses the SDK)
- [migrate tool](https://github.com/radio4000/migrate-tool) { [site](https://migrate.radio4000.com) } a React app for migration a radio and tracks
- [sdk](https://github.com/radio4000/sdk) { [npm](https://www.npmjs.com/package/@radio4000/sdk), [site](https://radio4000.github.io/sdk) } a javascript Software Development Kit, to have all necessary functions to communicate with r4
- [supabase](https://github.com/radio4000/supabase), the new backend (it uses [supabase](https://supabase.com), which provides us with database, authentication, internal APIs, edge functions, realtime subscriptions, and storage

Next to be migrated to the new systems:

- [internet4000/radio4000-player](https://github.com/internet4000/radio4000-player) { [npm](https://www.npmjs.com/package/radio4000-player), [site](https://player.radio4000.com) }, currently relying on firebase
- [radio4000/api](https://github.com/radio4000/api) { [site](https://api.radio4000.com) }, currently relying on firebase

\* all welcome to ask any question or chat on [#radio4000:matrix.org](https://matrix.to/#/#radio4000:matrix.org); visit [github/internet4000](https://github.com/internet4000) for other projects and previous r4 versions
