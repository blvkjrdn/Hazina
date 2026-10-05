Hazina Circle

A front-end prototype of a private investment syndication platform for Kenyan members. It is a single-page simulation with no backend; all data is placeholder.

Features

- Portfolio: total value, projected net annual yield, an animated wealth growth chart with hover tooltips, and an allocation breakdown.
- Opportunities: curated syndicate deals with live pooling progress bars and a "reserve your share" flow.
- Community: members submit deals and vote on pending proposals.

Run it

Open `index.html` in any modern browser. No build step or dependencies; the only external request is Google Fonts.

Deploy on GitHub Pages

1. Keep the page as `index.html` in the folder Pages publishes from.
2. In Settings → Pages, choose that branch and folder.
3. Visit `https://<username>.github.io/<repo>/`.

Customise

Colours and fonts are CSS variables at the top of the `<style>` block. Deals and proposals are the `deals` and `props` arrays in the `<script>` block.

Note

Figures, names and returns are illustrative only and are not financial advice.
