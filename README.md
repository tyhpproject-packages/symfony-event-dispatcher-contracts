<!-- tyhp-readme:start -->
# tyhpdef/symfony-event-dispatcher-contracts

Tyhp type definitions for `symfony/event-dispatcher-contracts` `3.7.1`.

```bash
composer require --dev tyhpdef/symfony-event-dispatcher-contracts:3.7.1
```

This is a metapackage. Composer also installs `tyhpdef/symfony-event-dispatcher-contracts-impl` (type files).
Require **this** name, not `tyhpdef/symfony-event-dispatcher-contracts-impl`.

See https://tyhplang.com.

## Maintain `symfony/event-dispatcher-contracts`? Ship the types yourself

If you are a Packagist maintainer of `symfony/event-dispatcher-contracts`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/symfony-event-dispatcher-contracts-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `symfony/event-dispatcher-contracts` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/symfony-event-dispatcher-contracts": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `symfony/event-dispatcher-contracts` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `symfony/event-dispatcher-contracts` with a real constraint,
   `"replace": { "tyhpdef/symfony-event-dispatcher-contracts": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `symfony/event-dispatcher-contracts` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/symfony-event-dispatcher-contracts` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
