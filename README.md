# selah-assets

Print masters for the Selah store. Printful fetches these over HTTPS, so they
must be public. Every art URL sent to the provider is pinned to a commit SHA,
never to a branch head: raw.githubusercontent caches branch heads for minutes
and will serve stale art at the wrong aspect ratio.

