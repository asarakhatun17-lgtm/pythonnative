# CHANGELOG


## v0.1.0 (2026-09-05)

### Bug Fixes

- Address library bugs uncovered by the E2E suite
  ([`c7becef`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/c7becefd63ed46cc3a2922df5e7731231c22e0bf))

- Pin PythonKit to v0.5.1 after upstream renamed master to main
  ([#13](https://github.com/asarakhatun17-lgtm/pythonnative/pull/13),
  [`e787891`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/e787891a72e62526f70effc21cb70f37898c5de9))

- **components,templates**: Restore hello-world on iOS and Android
  ([`d7ac93b`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/d7ac93be202161a5c8328816a5c6ff8a96dde1d5))

- **hot_reload,native_views**: Dedupe per-host reloads; clamp NaN frames
  ([`796ec70`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/796ec70936a3ba127c42aaa2eafdc3f0362690b9))

- **native_views**: Wire return_key_type on Android, and dismiss keyboard
  ([`3ab5d98`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/3ab5d987144bb5172c491798b32b34c6f3f44d39))

- **screen**: Preserve hook state across Android pop-back
  ([`6b27f0c`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/6b27f0cacfd8be36a19790c58e93686b9617f15b))

### Build System

- **deps**: Drop Python 3.9 support (EOL October 2025)
  ([`552cd99`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/552cd9958c463a51af9e33f0e254dab18135130f))

- **pyproject,scripts,workflows**: Migrate development tooling from pip to uv
  ([#47](https://github.com/asarakhatun17-lgtm/pythonnative/pull/47),
  [`c90bbcb`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/c90bbcbed9f027536412c859a01026e73252d2ad))

Refs: #28

- **repo**: Remove invalid PyPI classifier
  ([`c8552e1`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/c8552e137e0176c0f5c61193e786429e2e93ac7c))

- **templates,cli**: Ship template dirs with package; drop zip artifacts
  ([`7725b14`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/7725b1462c42d89f27fb4d3d733e73177c55d8ac))

### Chores

- Clean up
  ([`6c7a882`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/6c7a882895691903457a0a94d33192b6018c77fd))

- **core,components,cli**: Align lint, typing, and tests with CI
  ([`30037d1`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/30037d17ad397952a88e3dfeb8bd003ced7319d8))

- **examples**: Use existing AOSP drawable names for Android tab icons
  ([`0767170`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/0767170f937eef675b1e6328ec4ef828354ef2f3))

- **experiments**: Remove experiments directory
  ([`caf6993`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/caf69936e085a3f487123ebcb3a6d807fefcc66c))

- **experiments**: Remove unused experiment directories
  ([`db06fd1`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/db06fd101789392deee8c37263a61ee4d7106853))

- **repo,ci,docs**: Rename demo to examples/hello-world and update refs
  ([`6d5b78e`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/6d5b78ea7dce66b5031b952928aed8d4a713fae8))

- **repo,core,mkdocs**: Bump version to 0.2.0
  ([`d3f8d31`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/d3f8d31942c3ca5d1657024e3a5cb332787afcd8))

- **repo,core,mkdocs**: Bump version to 0.3.0
  ([`64d7c1c`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/64d7c1cfb448797305efc7f4014e56584f92fc1a))

- **scripts**: Add Android emulator launcher
  ([`ab6b4ae`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/ab6b4ae98a23c4d729e4ccb5ee4148ed4b4a6612))

- **scripts**: Add check.sh to run ci.yml checks locally
  ([`6bcb874`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/6bcb874fe287e6b57036fb207bac28d24e29eb2a))

- **templates**: Scrub DEVELOPMENT_TEAM from iOS template
  ([`64ab266`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/64ab2666fe09f036934d3922ab55e8e599df3c35))

### Code Style

- **cli**: Reformat pn.py for Black 2026 stable style
  ([`298f884`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/298f884ce3e1c58a17c92484c5832ebae6f1beaa))

### Continuous Integration

- **workflows**: Add Maestro E2E tests for Android and iOS
  ([`cfe247e`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/cfe247edf99da8ff870e2d4118ef74b2df5521c1))

- **workflows**: Add package build step to verify sdist and wheel before release
  ([`7fbf9c0`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/7fbf9c07988d4c543253dec8ba28da42c38cc3a9))

- **workflows**: Add semantic-release pipeline and PR commit linting
  ([`0711683`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/0711683f5b56751027bb1a5a63ee2d9afcd4b620))

- **workflows**: Append detailed changes link to release notes
  ([`11d50a7`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/11d50a75dff850a3855a299f38f5885cf15cefc6))

- **workflows**: Fix duplicate release, and use changelog for release notes
  ([`1cd5393`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/1cd5393e7bf20d5350052cfaa81fd511dc4ca3ca))

- **workflows**: Shard the iOS E2E run across simulators
  ([`536fed6`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/536fed6c1cd0a7c069aa9c3d1ff42941fa65da08))

- **workflows**: Simplify release pipeline to use python-semantic-release defaults
  ([`2766f24`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/2766f244f84d359e1ae74a4b029e0701fad4b0be))

- **workflows,cli**: Fix e2e workflow script chaining and GitHub API auth
  ([`01d1968`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/01d19683f41a4b00048dfbce687e510bec2e2d31))

- **workflows,mkdocs**: Set CNAME to docs.pythonnative.com for docs deploy
  ([`401a076`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/401a076dcb1fe0c19771f4a19141ee8da28c80e2))

- **workflows,scripts**: Shard the Android E2E run across emulators
  ([`67c340d`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/67c340d2117b4282d64081374d4d5ce6ab5c01fe))

- **workflows,tests**: Stabilize Android E2E on CI
  ([#4](https://github.com/asarakhatun17-lgtm/pythonnative/pull/4),
  [`2488faf`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/2488fafd7c24590be4f442475f5fc8e114d61e7b))

### Documentation

- Add AGENTS.md with documentation style guidelines
  ([`1e860b7`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/1e860b7ee40f933b29e7d94d3c9cbedac873b6f6))

- Adopt Google-style docstrings; revamp MkDocs site
  ([`922ec94`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/922ec94bee841c8309b9b26a0c5085f663addb11))

- Align branch prefixes with conventional commit types
  ([`c6e0e08`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/c6e0e08cb0757dad6495c6fee36063699afba87a))

- Serve documentation site from the apex domain
  ([`6b659e9`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/6b659e9c5bb1631891cd35cc4b179ee5e3e26e44))

- Strip AI provenance metadata from logo image
  ([`d1dfe98`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/d1dfe98ebf9d3a4561bfaebe3dfe9284c2b3616a))

- Use straight quotes, and drop em dashes per style guide
  ([#12](https://github.com/asarakhatun17-lgtm/pythonnative/pull/12),
  [`6c0399c`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/6c0399c4c2a3f5452e04edbc1ac2a709c411ad3f))

- **events,mutations,platform_metrics**: Add API reference pages
  ([#31](https://github.com/asarakhatun17-lgtm/pythonnative/pull/31),
  [`a9b5147`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/a9b51472fa9112973e5304b84bb3dfc0c89885f1))

- **mkdocs**: Add Architecture page
  ([`6d61ffc`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/6d61ffc64ca5db8ae688d09a748ddda2a1bc0af6))

- **mkdocs**: Add roadmap and link in nav
  ([`16ede97`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/16ede972d41b549853962c7056b65558c9ebd2f5))

- **mkdocs**: Mention pn preview in the hello-world example
  ([#50](https://github.com/asarakhatun17-lgtm/pythonnative/pull/50),
  [`60687a0`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/60687a0940438547270a2be0f9fce9b9ce66b605))

Refs: #42

Co-authored-by: Owen Carey <37121709+owenthcarey@users.noreply.github.com>

- **mkdocs**: Reconcile package overview with main
  ([`2802206`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/2802206381fcdb7496d48afb47de1f780f94edbd))

Preserve the current hosts and utilities references while retaining the CLI reference link and
  restoring the CLI label spacing.

- **mkdocs**: Refresh package overview internals and CLI lists
  ([`6180559`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/6180559435a667c27ea09b9d0d5747a123f2b436))

Updated documentation for CLI to include additional references.

- **mkdocs**: Tell readers how to run the example snippets
  ([#65](https://github.com/asarakhatun17-lgtm/pythonnative/pull/65),
  [`b1e6507`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/b1e6507fe84c208f7dfd898c26341d545e4610d6))

Refs: #52

- **mkdocs**: Update Getting Started, Hello World, Components, and platform guides
  ([`f3a03b0`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/f3a03b01986365063535a2f336793cc6f21836db))

- **mutations**: Add Attributes sections to the remaining op docstrings
  ([#66](https://github.com/asarakhatun17-lgtm/pythonnative/pull/66),
  [`9cb8f9b`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/9cb8f9b2f6dbe3fde02af44ff7f85031c568c948))

Refs: #61

- **navigation**: Fix use_route and Stack.Screen examples
  ([#51](https://github.com/asarakhatun17-lgtm/pythonnative/pull/51),
  [`7e59651`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/7e596518155a00f0379542bcecddd8855d05127a))

Refs: #36

Co-authored-by: Owen Carey <37121709+owenthcarey@users.noreply.github.com>

- **platform**: Document the desktop OS value and is_desktop
  ([#64](https://github.com/asarakhatun17-lgtm/pythonnative/pull/64),
  [`fcacf86`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/fcacf86df77bada7b01343d56b5f455df0a691ff))

Refs: #39

Co-authored-by: Owen Carey <37121709+owenthcarey@users.noreply.github.com>

- **repo**: Add CONTRIBUTING.md
  ([`f61cb85`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/f61cb85301c7bff57299b4c814319e9262f0f5ef))

- **repo**: Add missing module scopes to CONTRIBUTING
  ([`5a02f04`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/5a02f045e91a6f5fb6569e63f4a1081616a3e52c))

- **repo**: Align conventional commit scopes with module structure
  ([`ecc39af`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/ecc39af78708bc5a83ba81501c7b65d985890de9))

- **repo**: Document issue claiming before opening PRs
  ([`3223619`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/3223619cc4c3b63f46a63294a47bac7952e17dac))

- **repo**: Remove component table from README
  ([`ab162c5`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/ab162c5b658b2367857ab998d3b3f750eca15b4a))

- **repo**: Rewrite README with banner, structured sections, and badges
  ([`7c083f4`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/7c083f4e38367c6cd4163e0be8c78da1fdf8d3da))

- **repo**: Simplify README with badges and one-paragraph overview
  ([`3ac84b1`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/3ac84b1a3f541b47121b46a687b78826f8d348f9))

### Features

- Add function components, hooks, layout, styling, hot reload, native APIs, and new UI components
  ([`3bd87de`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/3bd87de4a8775e23eb4f081a31b9125f9b20861c))

- Add native lists, dark mode, rich text, and image pipeline
  ([#15](https://github.com/asarakhatun17-lgtm/pythonnative/pull/15),
  [`c609a94`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/c609a941c230a7e92269f97dae775d3619ff1907))

- Add pythonnative.toml config and build system
  ([#10](https://github.com/asarakhatun17-lgtm/pythonnative/pull/10),
  [`869e977`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/869e9776b02628102bff7d76b67d2663d606915e))

- Add typed components, navigation overhaul, and testing
  ([#70](https://github.com/asarakhatun17-lgtm/pythonnative/pull/70),
  [`d0294a7`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/d0294a70918813a9e7762ce0d151b8a31cb634c7))

- Overhaul animations, gestures, and interaction props
  ([#19](https://github.com/asarakhatun17-lgtm/pythonnative/pull/19),
  [`75cd0ca`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/75cd0ca57daede85bd30549316832968576056ec))

- Overhaul core semantics, dev diagnostics, and public API
  ([#16](https://github.com/asarakhatun17-lgtm/pythonnative/pull/16),
  [`985d7ca`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/985d7ca258a15d0452db5816a7680f2626ea1f45))

- Overhaul native bridge, animations, gestures, and lists
  ([#11](https://github.com/asarakhatun17-lgtm/pythonnative/pull/11),
  [`b635110`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/b635110fe7139d39f2ae7830fe99177eb03dc0bb))

- Replace class-based Page with function components, style prop, and use_navigation hook
  ([`8103710`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/8103710aed5feb564583bb161cf81771669645fe))

- Update README
  ([`e839585`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/e8395855acf5d38a0e5987475900f4eeb1eee313))

- **bridge**: Add native rendering core and module plugins
  ([#72](https://github.com/asarakhatun17-lgtm/pythonnative/pull/72),
  [`6c7d4d4`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/6c7d4d473769cca6978f990d844c3127369e327f))

- **cli**: Add --device flag to pn logs
  ([#67](https://github.com/asarakhatun17-lgtm/pythonnative/pull/67),
  [`6d3a171`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/6d3a1713246dcb887caadcfa085a05dbcbeb8ed9))

Refs: #38

Co-authored-by: Owen Carey <37121709+owenthcarey@users.noreply.github.com>

- **cli**: Add --json output to pn devices
  ([#30](https://github.com/asarakhatun17-lgtm/pythonnative/pull/30),
  [`4efea4d`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/4efea4d25387c7062db78b448d776e0b85dc0452))

Refs: #22

- **cli**: Add --version flag ([#26](https://github.com/asarakhatun17-lgtm/pythonnative/pull/26),
  [`5ceb010`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/5ceb010f42c8e2c209b9490ab6a4d2a142a28ff6))

Refs: #20

- **cli**: Add dev server, dev clients, and browser preview
  ([#74](https://github.com/asarakhatun17-lgtm/pythonnative/pull/74),
  [`ee66d34`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/ee66d340178c5a5a082fc0f02ad0b1c01bc0e6d9))

- **cli**: Check for Tkinter in pn doctor
  ([#25](https://github.com/asarakhatun17-lgtm/pythonnative/pull/25),
  [`5cd7953`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/5cd79534c6b087afe8287570574b37438cfb5981))

Refs: #23

- **cli**: Create project directory in pn init <name>
  ([#27](https://github.com/asarakhatun17-lgtm/pythonnative/pull/27),
  [`5f84246`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/5f84246da722ed077864dd060f3322d47ae4ee76))

Refs: #21

- **cli**: Overhaul ios embedding, devices, and release builds
  ([#18](https://github.com/asarakhatun17-lgtm/pythonnative/pull/18),
  [`c200d2a`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/c200d2a390ee3a6f92875ffe04fb063c78ca88f4))

- **cli**: Validate project names and escape TOML values
  ([#32](https://github.com/asarakhatun17-lgtm/pythonnative/pull/32),
  [`3e78f6e`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/3e78f6ea20084da0b5a419b17be5fa40e8575128))

Refs: #29

- **cli,mkdocs,tests**: Add pn init/run/clean; use bundled templates
  ([`9c61757`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/9c61757713fe60b5e98756f552681a782f397f3a))

- **cli,page,templates**: Stream Python logs from pn run android/ios
  ([`57179b9`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/57179b9c3946486aac6eb37a38dbdaa8755335b2))

- **cli,templates**: Add pythonVersion config, fix Android build, and wire pip requirements
  ([`a529834`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/a529834a7bfe817a51ef2a5846c97c2f4deee321))

- **cli,templates**: Auto-select iOS sim; guard PythonKit
  ([`7b7c59c`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/7b7c59c262f2510a5fb46e455c13a2fc56086845))

- **cli,templates**: Bundle offline templates; add run --prepare-only
  ([`d9dd821`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/d9dd821bc18289f1f1a367e737cfe7d5bfaf6ee3))

- **cli,templates**: Dev-first templates; stage in-repo lib for pn run
  ([`b3dd731`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/b3dd731bd5efcca8e1a47f8f888fc6123854a40c))

- **cli,templates,core**: Bootstrap entrypoint; pn run shows Hello UI
  ([`2805e1d`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/2805e1d5c6a58eb718b94ba0ce57c1078a08d578))

- **cli,templates,core**: Fetch iOS Python runtime and bootstrap PythonKit
  ([`bcc0916`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/bcc0916a5b7427874ab7a5971a6a9941c4222c77))

- **components**: Standardize fluent setters and align base signatures
  ([`d236d89`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/d236d899690a4033effdcab4862a556a742fa6d1))

- **components,core**: Add layout/styling APIs and fluent setters
  ([`6962d38`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/6962d3881bf091b3494fc2c964f7ea65a99ce606))

- **components,hooks**: Add props, fragment, memo, and native picker
  ([`54878c0`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/54878c0ceed67219b2f70ebd435020243a1fea7d))

- **components,hooks,native_views**: Add native UI primitives
  ([`186bba6`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/186bba6dcc1956cccb1433e004e4fb9b436736ce))

- **components,native_modules**: Expand component and device APIs
  ([#7](https://github.com/asarakhatun17-lgtm/pythonnative/pull/7),
  [`1d6fe92`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/1d6fe9282a3b85617b77532cd0bd79122cb06a87))

- **components,utils**: Unify constructors; set Android context
  ([`4c06b67`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/4c06b67214ea7fc4530a0d39b7105cfb62d20cf5))

- **core**: Replace imperative widget API with declarative component model and reconciler
  ([`b6b7721`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/b6b77216305202ea0c5197b29e725e14cbe99b5e))

- **core,templates**: Add push/pop navigation and lifecycle wiring
  ([`06ea22d`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/06ea22d215a1700685a7ca8070ca2189895ed25c))

- **hooks,reconciler**: Defer effects; add batching and use_reducer
  ([`bf6bb57`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/bf6bb57b6f97c140820a902ea0eff6bf6a7ffdbc))

- **hot_reload**: Reload Python app code without rebuilding
  ([`cddbcdc`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/cddbcdc1bfd57ea2362116f0a8e0b1f8c98ca8f9))

- **layout**: Add pure-Python flexbox engine; rewrite native containers
  ([`4247386`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/42473866ee7c2380e6c38f4e42966c64ca3c2bb8))

- **native_views,cli**: Add desktop preview backend and pn preview
  ([#8](https://github.com/asarakhatun17-lgtm/pythonnative/pull/8),
  [`3228f11`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/3228f11b4fc70f92c8fede4b03639f8eb51bc24c))

- **native_views,components**: Add flexbox-inspired layout system
  ([`094d997`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/094d99786f7153a7286eb7db9775db0bb90abf1d))

- **navigation**: Add declarative navigation system
  ([`828bbb0`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/828bbb0c83fba640a7055edf1237500f27493fd3))

- **navigation**: Add native tab bars and nested navigator forwarding
  ([`2b80032`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/2b8003218267dd39b968c630b89bd5e212ea7254))

- **navigation**: Add tab_bar_icon option for native system icons
  ([`baf6d58`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/baf6d58e90783953304d5cba8c05d5878bee1a57))

- **net**: Add concise __repr__ to Response
  ([#49](https://github.com/asarakhatun17-lgtm/pythonnative/pull/49),
  [`2ffc701`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/2ffc701fc325a4b18b0519368e95602162763cc6))

Refs: #43

- **package**: Export get_platform
  ([#48](https://github.com/asarakhatun17-lgtm/pythonnative/pull/48),
  [`05e2391`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/05e23919607b13149fc629f58d8918fb62c43fb3))

Refs: #44

- **project,cli**: Resolve PyPI deps per target, and tighten API
  ([#73](https://github.com/asarakhatun17-lgtm/pythonnative/pull/73),
  [`8cebee5`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/8cebee5e1f4b9d50d366a3db7608131bb01e1531))

- **reconciler**: Re-render only dirty components, not the whole tree
  ([#9](https://github.com/asarakhatun17-lgtm/pythonnative/pull/9),
  [`13b615d`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/13b615df2c0a85b77f9c2f16a6349c7e93faaa82))

- **repo,mkdocs,workflows**: Migrate to src layout; add pyproject and docs scaffold
  ([`f273922`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/f273922e8a0494df7ba2cd59a3ad2ef54f918d3e))

- **runtime**: Add asyncio loop and awaitable APIs
  ([#5](https://github.com/asarakhatun17-lgtm/pythonnative/pull/5),
  [`6b468fd`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/6b468fd98031466e00c1df9732f4c1f28188eb0d))

- **runtime,hooks**: Make rendering async-first with Suspense
  ([#17](https://github.com/asarakhatun17-lgtm/pythonnative/pull/17),
  [`a011d59`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/a011d5934aab500efddd6a452027814ad8f961b0))

- **screen,hot_reload**: Add native stack navigation and Fast Refresh
  ([#1](https://github.com/asarakhatun17-lgtm/pythonnative/pull/1),
  [`042f411`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/042f4116f0342b90c7a6ee0f9a28bf8c075507c3))

- **sdk,style**: Add native-component SDK and typed Style API
  ([#2](https://github.com/asarakhatun17-lgtm/pythonnative/pull/2),
  [`9f26a6e`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/9f26a6e3482c6fb81d7522159b2916fa0855a283))

- **templates,core**: Adopt Fragment-based Android navigation
  ([`7a3a695`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/7a3a695477ece3cf76afd00f203523990f8789df))

### Refactoring

- **cli**: Make pn.py typing py3.9-compatible and wrap long lines
  ([`b38da78`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/b38da78dac52e42968efa6f4115b6b84de65b3b5))

- **components**: Declare abstract static wrap in ScrollViewBase
  ([`593fee4`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/593fee4fcf66678cb026de58115f959633d859b4))

- **components,core**: Align component names with docs
  ([`a326ceb`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/a326ceb23c2cfaba409f11451a1c0000f0afbf5e))

- **core,components,examples**: Add annotations; tighten mypy
  ([`86e4ffc`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/86e4ffc9e51810997006055434783416784c182f))

- **native_views**: Split monolithic module into platform-specific package
  ([`d0068fd`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/d0068fdbcceb4745b02d8043b03eade2b54dde66))

### Testing

- Add e2e-suite covering every public API
  ([`38e3e01`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/38e3e013bc51f951215c142f22515000e355a1ef))

- Increase app startup wait for slow CI emulators
  ([`4ff6b94`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/4ff6b9453a7687eeaf7777bf4a2ab542b32a7e25))

- Make e2e open_demo state-aware to skip redundant relaunches
  ([`a94859f`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/a94859f9b6c31ca6203ce76fbbcbd3ac7d937d54))

- Match full PythonNative version text in settings e2e flow
  ([`5198051`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/5198051e2a1bcfcccb47e148a92df0185917ff5e))

- **examples**: Use scrollUntilVisible for scroll_view/flat_list
  ([`5b8af35`](https://github.com/asarakhatun17-lgtm/pythonnative/commit/5b8af354f51c52549ef6e368ca8d85800eddb389))
