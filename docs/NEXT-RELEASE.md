# Next release: move the web addresses

On 2026-11-10 the code moved to **github.com/justpuzzles/numeriqo**. The old
repo **kkai/numeriqo** stays, only to serve the pages the live app and its App
Store listing point at. Don't delete it: that would take
kaikunze.de/numeriqo/ offline.

In the next release, once the app's page exists at justpuzzles.app/numeriqo/
(see "Websites" in the workspace README):

- [ ] ASC version: Support URL and Marketing URL
      kaikunze.de/numeriqo/ → https://justpuzzles.app/numeriqo/
- [ ] ASC App Information: Privacy Policy URL
      kaikunze.de/numeriqo/numeriqo-privacy.html → https://justpuzzles.app/numeriqo/privacy/
- [ ] In-app links (Settings / About) that still say kaikunze.de/numeriqo/
- [ ] After that release is live: turn kkai/numeriqo's gh-pages into
      redirects to the new pages (old binaries keep their links), then
      archive kkai/numeriqo.

Local clones have two remotes: `origin` (justpuzzles, code) and `kaikunze`
(kkai, the old pages). Push code to `origin` only.
