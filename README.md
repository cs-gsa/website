# csgsa website

## description
- The csgsa website

## code
- The website uses `zola` static site generator.
- Find a tutorial for `zola` [here](https://www.getzola.org/).
- `master` branch of this repo contains the source code.
- `gh-pages` contains the generated site and is served using github pages.

## documentation
- The documentation of the source code is itself.

## usage

### how to make changes?
- Learn `zola`.
- Make changes in source code (`master` branch).
- After making changes, make sure the umn branding rules are adhered to, which can be found [here](https://university-relations.umn.edu/resources/website-header-footer-and-templates).
    - The site can be revoked if these are not adhered to.
- Use `zola build` to build the entire site in `public/`.
- Copy the contents of `public` to `gh-pages` as-is.
- Push to github and the site should be live.

### what kind of changes to make or not make?
- Please keep the site minimal and maintainable
- Avoid adding big headers which increase loading time, fancy one-time useful stuff that is not easy to maintain etc...
- The goal is to have a snappy website and minimal friction for future maintainers.

## roadmap
- [x] link to global static css/js.
- [x] nav bar.
- [x] shortcodes.

## license
- Please do not copy.
