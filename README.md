# dummynamestudio.github.io

The website of DummyName Studio, published by GitHub Pages at <https://dummynamestudio.github.io/>.

* `index.html` - the studio's page with the list of games.
* `<game>/privacy-policy.html` - the privacy policy of each game (`bouncy/` for Bouncy). Its URL
  goes into Play Console (*App content -> Privacy policy*), AdMob (*Privacy & messaging*) and the
  game's own Settings screen.
* `app-ads.txt` - authorised ad sellers, one file for all games (it must be at the root of the
  developer website set in each game's Play Console store listing).
* `style.css` - shared look.

To add a game: copy `bouncy/` to a folder named after the game, adapt its privacy policy (the
services the game uses) and add the game to `index.html`. Pushing to `main` publishes the site.
