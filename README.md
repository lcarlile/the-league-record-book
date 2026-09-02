# The League — Record Book

Live: https://lcarlile.github.io/the-league-record-book/

This repo holds only the published page. It is **generated** — do not edit `index.html` here.
The source, data pipeline and design live in `loog-record-book`, which builds this page and
publishes it:

```sh
cd ../loog
./refresh.sh --league the-league   # pull ESPN, recompute
node build.js --league the-league  # rebuild the page
./publish.sh the-league            # copy here, commit, push
```
