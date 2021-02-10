# v2.12.2 (Wed Feb 10 2021)

#### 🐛 Bug Fix

- turn off jsdoc/no-types for jsx files [#620](https://github.com/intuit/design-systems-cli/pull/620) ([@Talor-A](https://github.com/Talor-A))
- turn off jsdoc/no-types for jsx files ([@Talor-A](https://github.com/Talor-A))

#### Authors: 1

- Talor Anderson ([@Talor-A](https://github.com/Talor-A))

---

# v2.11.0 (Thu Jan 07 2021)

#### 🚀 Enhancement

- Add eslint local dependency rule to ds lint [#608](https://github.com/intuit/design-systems-cli/pull/608) ([@kendallgassner](https://github.com/kendallgassner))

#### 🐛 Bug Fix

- merge with master ([@kendallgassner](https://github.com/kendallgassner))
- add link and file plugin rule ([@kendallgassner](https://github.com/kendallgassner))

#### Authors: 1

- Kendall Gassner ([@kendallgassner](https://github.com/kendallgassner))

---

# v2.0.0 (Fri Aug 14 2020)

### Release Notes

_From #365_

WDIO Breaking changes:

- host -> hostname in proof.config.js
- Change all tests to use wdio updated APIs
- Removal of assert from proof. Consumer provides their own assertion library now

---

#### 💥 Breaking Change

- Upgrade to "proof" v0.1.0 [#365](https://github.com/intuit/design-systems-cli/pull/365) ([@vasikarla](https://github.com/vasikarla) [@hipstersmoothie](https://github.com/hipstersmoothie) [@adierkens](https://github.com/adierkens))

#### 🚀 Enhancement

- feat: adding ability to send failure threshold from args [#275](https://github.com/intuit/design-systems-cli/pull/275) ([@vasikarla](https://github.com/vasikarla))
- lint mdx files [#283](https://github.com/intuit/design-systems-cli/pull/283) ([@hipstersmoothie](https://github.com/hipstersmoothie))

#### 🐛 Bug Fix

- Update dependency tslib to v2 ([@renovate-bot](https://github.com/renovate-bot))
- only require jsdoc for arrow functions assigned to variable [#440](https://github.com/intuit/design-systems-cli/pull/440) ([@hipstersmoothie](https://github.com/hipstersmoothie))
- disable require-jsdoc on more ArrowExpression cases [#438](https://github.com/intuit/design-systems-cli/pull/438) ([@hipstersmoothie](https://github.com/hipstersmoothie))
- add more contexts to ignore arrow functions in ([@hipstersmoothie](https://github.com/hipstersmoothie))
- disable require-jsdoc on more ArrowExpression cases ([@hipstersmoothie](https://github.com/hipstersmoothie))
- Update dependency eslint-plugin-no-explicit-type-exports to v0.11.4 ([@renovate-bot](https://github.com/renovate-bot))
- Update dependency eslint-plugin-jsdoc to v30.2.2 ([@renovate-bot](https://github.com/renovate-bot))
- Merge master into next ([@hipstersmoothie](https://github.com/hipstersmoothie))
- only require jsdoc for arrow functions assigned to variable ([@hipstersmoothie](https://github.com/hipstersmoothie))
- Update dependency eslint-plugin-react to v7.20.6 ([@renovate-bot](https://github.com/renovate-bot))
- Update linters ([@renovate-bot](https://github.com/renovate-bot))
- Bump version to: v1.10.0 \[skip ci\] ([@hipstersmoothie](https://github.com/hipstersmoothie))
- lint mdx files ([@hipstersmoothie](https://github.com/hipstersmoothie))
- fix lint ([@hipstersmoothie](https://github.com/hipstersmoothie))
- Update typescript-eslint monorepo to v3 ([@hipstersmoothie](https://github.com/hipstersmoothie))
- Update linters ([@hipstersmoothie](https://github.com/hipstersmoothie))

#### 🔩 Dependency Updates

- Update dependency babel-plugin-styled-components to v1.11.1 [#390](https://github.com/intuit/design-systems-cli/pull/390) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency @types/semver to v7.3.2 [#429](https://github.com/intuit/design-systems-cli/pull/429) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency eslint-plugin-no-explicit-type-exports to v0.11.4 [#431](https://github.com/intuit/design-systems-cli/pull/431) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency eslint-plugin-jsdoc to v30.2.2 [#421](https://github.com/intuit/design-systems-cli/pull/421) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency fork-ts-checker-webpack-plugin to v5 [#415](https://github.com/intuit/design-systems-cli/pull/415) ([@renovate-bot](https://github.com/renovate-bot) [@hipstersmoothie](https://github.com/hipstersmoothie) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency css-loader to v4 [#414](https://github.com/intuit/design-systems-cli/pull/414) ([@renovate-bot](https://github.com/renovate-bot) [@hipstersmoothie](https://github.com/hipstersmoothie) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency jest to v26.4.0 [#419](https://github.com/intuit/design-systems-cli/pull/419) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency tslib to v2 [#385](https://github.com/intuit/design-systems-cli/pull/385) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency progress-estimator to v0.3.0 [#406](https://github.com/intuit/design-systems-cli/pull/406) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency postcss-nested to v4.2.3 [#405](https://github.com/intuit/design-systems-cli/pull/405) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency @types/node to v14 [#412](https://github.com/intuit/design-systems-cli/pull/412) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency colorette to v1.2.1 [#394](https://github.com/intuit/design-systems-cli/pull/394) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency commently to v6.0.2 [#430](https://github.com/intuit/design-systems-cli/pull/430) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency @types/clean-css to v4.2.2 [#387](https://github.com/intuit/design-systems-cli/pull/387) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency type-fest to v0.16.0 [#407](https://github.com/intuit/design-systems-cli/pull/407) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency webpack-cli to v3.3.12 [#408](https://github.com/intuit/design-systems-cli/pull/408) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency @types/eslint to v7 [#410](https://github.com/intuit/design-systems-cli/pull/410) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency @types/jest to v26 [#411](https://github.com/intuit/design-systems-cli/pull/411) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency @types/webpack-sources to v1 [#413](https://github.com/intuit/design-systems-cli/pull/413) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency jest-junit to v11 [#416](https://github.com/intuit/design-systems-cli/pull/416) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update dependency eslint-plugin-react to v7.20.6 [#418](https://github.com/intuit/design-systems-cli/pull/418) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update linters [#374](https://github.com/intuit/design-systems-cli/pull/374) ([@renovate-bot](https://github.com/renovate-bot) [@hipstersmoothie](https://github.com/hipstersmoothie) [@renovate[bot]](https://github.com/renovate[bot]))
- Update stylelint [#376](https://github.com/intuit/design-systems-cli/pull/376) ([@hipstersmoothie](https://github.com/hipstersmoothie) [@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Upgrade Ts eslint [#269](https://github.com/intuit/design-systems-cli/pull/269) ([@hipstersmoothie](https://github.com/hipstersmoothie))
- Update linters [#265](https://github.com/intuit/design-systems-cli/pull/265) ([@hipstersmoothie](https://github.com/hipstersmoothie))

#### Authors: 5

- [@renovate[bot]](https://github.com/renovate[bot])
- Adam Dierkens ([@adierkens](https://github.com/adierkens))
- Andrew Lisowski ([@hipstersmoothie](https://github.com/hipstersmoothie))
- Raj Vasikarla ([@vasikarla](https://github.com/vasikarla))
- WhiteSource Renovate ([@renovate-bot](https://github.com/renovate-bot))

---

# v1.4.7 (Tue Mar 24 2020)

:tada: This release contains work from a new contributor! :tada:

Thank you, WhiteSource Renovate ([@renovate-bot](https://github.com/renovate-bot)), for all your work!

#### 🔩 Dependency Updates

- Update dependency tslib to v1.11.1 [#152](https://github.com/intuit/design-systems-cli/pull/152) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))
- Update linters [#128](https://github.com/intuit/design-systems-cli/pull/128) ([@renovate-bot](https://github.com/renovate-bot) [@renovate[bot]](https://github.com/renovate[bot]))

#### Authors: 2

- [@renovate[bot]](https://github.com/renovate[bot])
- WhiteSource Renovate ([@renovate-bot](https://github.com/renovate-bot))

---

# v1.2.5 (Thu Jan 30 2020)

#### 🐛  Bug Fix

- Edit ts linting rule  ([@hipstersmoothie](https://github.com/hipstersmoothie))

#### Authors: 1

- Andrew Lisowski ([@hipstersmoothie](https://github.com/hipstersmoothie))

---

# v1.2.4 (Wed Jan 29 2020)

#### 🐛  Bug Fix

- turn off eslint rule  ([@hipstersmoothie](https://github.com/hipstersmoothie))

#### Authors: 1

- Andrew Lisowski ([@hipstersmoothie](https://github.com/hipstersmoothie))

---

# v1.2.0 (Wed Jan 22 2020)

#### 🐛  Bug Fix

- lossen import/extensions rule  ([@hipstersmoothie](https://github.com/hipstersmoothie))
- Update linters  ([@renovate-bot](https://github.com/renovate-bot))
- Update typescript-eslint monorepo to v2.17.0  ([@renovate-bot](https://github.com/renovate-bot))

#### Authors: 2

- Andrew Lisowski ([@hipstersmoothie](https://github.com/hipstersmoothie))
- WhiteSource Renovate ([@renovate-bot](https://github.com/renovate-bot))

---

# v0.74.1 (Tue Jan 07 2020)

#### ⚠️  Pushed to master

- set access  ([@hipstersmoothie](https://github.com/hipstersmoothie))

#### Authors: 1

- Andrew Lisowski ([@hipstersmoothie](https://github.com/hipstersmoothie))