# [radio4000](https://radio4000.com) [ r4000, r4k, r4 ]

This github organisation is the new `alpha` version of radio4000 systems (migration to supabase, from dependency firebase).

The new architecture of repositories (WIP) is currently:

- [cms-astro](https://github.com/radio4000/cms-astro) { [site](https://cms-astro.pages.dev) }, the `cms` (will be the new radio4000.com), to organize the components in routes (now made with `astro`)
- [sdk](https://github.com/radio4000/sdk) { [npm](https://www.npmjs.com/package/@radio4000/sdk), [site](https://radio4000.github.io/sdk) } a javascript Software Development Kit, to have all necessary functions to communicate with r4
- [components](https://github.com/radio4000/components) { [npm](https://www.npmjs.com/package/@radio4000/components), [site](https://radio4000.github.io/components) } a set of web-components, used to create reusable UI (it uses the SDK)
- [supabase](https://github.com/radio4000/supabase), the new backend (it uses [supabase](https://supabase.com), which provides us with database, authentication, internal APIs, edge functions, realtime subscriptions, and storage

Next to be migrated to the new systems:

- [internet4000/radio4000-player](https://github.com/internet4000/radio4000-player) { [npm](https://www.npmjs.com/package/radio4000-player), [site](https://player.radio4000.com) }, currently relying on firebase
- [radio4000/api](https://github.com/radio4000/api) { [site](https://api.radio4000.com) }, currently relying on firebase

\* all welcome to ask any question or chat on [#radio4000:matrix.org](https://matrix.to/#/#radio4000:matrix.org); visit [github/internet4000](https://github.com/internet4000) for other projects and previous r4 versions
