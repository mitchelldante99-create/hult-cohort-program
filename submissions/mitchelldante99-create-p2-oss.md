## Upstream repo URL
https://github.com/rogerSuperBuilderAlpha/cursor-boston

## Upstream PR URL
https://github.com/rogerSuperBuilderAlpha/cursor-boston/pull/1707

## Merge status
Open - awaiting review (DCO sign-off in progress)

## Contribution summary
Added explicit return type annotations to `buildLiveSessionPaths` and `controlLiveSessionServer` in `lib/live-sessions/data-server.ts`. Related to issue #590. Verified with `tsc --noEmit` (clean) and full existing test suite for the file (21/21 passing, no behavior changes).