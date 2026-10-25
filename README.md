# Session replay player

Reusable rrweb-player 2.2.0 UI with local playback. No recordings, collector, application source or credentials are stored in this repository.

Small PR replay links carry a bounded gzip preview in their URL fragment, which browsers do not send to the hosting server. It loads and plays automatically. The fragment stays in the address bar so refresh and copying the URL preserve the replay. PR links pin a versioned player path to avoid stale browser caches. Full recordings remain in the PR artifact. Local `.json.gz` and `.json` file loading is also available. Network requests are blocked after page load.
