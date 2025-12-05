# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.1.0 (2025-12-05)


### ⚠ BREAKING CHANGES

* add support for configuring default squash and merge commit title and messages ([#3](https://github.com/gaima8-org/fork-terraform-github-repository/issues/3))
* allow computed values in v4 branch protections
* remove support for string list in branches variable
* provider version requirements
* add allow_auto_merge and bump minimum supported  provider version to v4.19.2
* Only support latest versions of Terraform and Official GitHub Terraform Provider
* Add 3.1 feature support.
* Add support for v4 using v3 compatible branch protections
* Add visibility parameter and deprecate private parameter

### Features

* Add 3.1 feature support. ([f7bc644](https://github.com/gaima8-org/fork-terraform-github-repository/commit/f7bc644d5f58091910c1a33f1840fce2fdf26c19))
* add allow_auto_merge and bump minimum supported  provider version to v4.19.2 ([8c8d61b](https://github.com/gaima8-org/fork-terraform-github-repository/commit/8c8d61b1ae1174f816a9e4b1b5eb0ab06ea55b03))
* add github pages block to repositories ([1f98adf](https://github.com/gaima8-org/fork-terraform-github-repository/commit/1f98adf5adb09f5f37c919fb331497c7871c937f))
* add support for configuring default squash and merge commit title and messages ([#3](https://github.com/gaima8-org/fork-terraform-github-repository/issues/3)) ([ee13dab](https://github.com/gaima8-org/fork-terraform-github-repository/commit/ee13dab6c4023c0d23f3f6d16d2e4e80a9f6b214))
* add support for encrypted secrets ([7945749](https://github.com/gaima8-org/fork-terraform-github-repository/commit/7945749a1f4994a28f5a2caa5459c157850c9edb))
* add support for encrypted secrets ([cb49cec](https://github.com/gaima8-org/fork-terraform-github-repository/commit/cb49cec471f34a084c440aeda0df2e13029851a1))
* add support for github_branches ([7e0400f](https://github.com/gaima8-org/fork-terraform-github-repository/commit/7e0400f6a9b70ce099f04e95b089ec3f930d7542))
* Add support for provider 5.x ([f94103f](https://github.com/gaima8-org/fork-terraform-github-repository/commit/f94103f086b2d9619bbf1462f2277bfd9faf2994))
* Add support for provider 5.x ([773846a](https://github.com/gaima8-org/fork-terraform-github-repository/commit/773846a89b92771bbb50c987b763e35b3c78e8c1))
* Add support for terraform v0.14.x ([0b86db8](https://github.com/gaima8-org/fork-terraform-github-repository/commit/0b86db8af7667d20b660aa59b897e1304221f50a))
* Add support for terraform v0.14.x ([c7c9b11](https://github.com/gaima8-org/fork-terraform-github-repository/commit/c7c9b11724332597a20d9cd8f57e31a805e2acb2))
* add support for terraform v0.15 ([8e4aff4](https://github.com/gaima8-org/fork-terraform-github-repository/commit/8e4aff4519ea8ca50474df8de6e218954c4edab8))
* add support for terraform v0.15 ([225e582](https://github.com/gaima8-org/fork-terraform-github-repository/commit/225e582516ebf9747f7d71df10d77d40bc60d469))
* add support for terraform v1.0 ([812001f](https://github.com/gaima8-org/fork-terraform-github-repository/commit/812001f1e3c21d8bc883e1afba4f984b0ef6000e))
* add support for the github_app_installation_repository resource ([6b6fb1e](https://github.com/gaima8-org/fork-terraform-github-repository/commit/6b6fb1e20d79a7ef2a829ea1ac8c8ff7b79f466d))
* Add support for v4 using v3 compatible branch protections ([d342afc](https://github.com/gaima8-org/fork-terraform-github-repository/commit/d342afcdd47116138db9cd496692b5896b2c26c5))
* add terradoc ([32c1e63](https://github.com/gaima8-org/fork-terraform-github-repository/commit/32c1e63555965c46bb2bf1dffefb7334f7402ce2))
* add terradoc ([fae03ce](https://github.com/gaima8-org/fork-terraform-github-repository/commit/fae03ce54bbe714a96fdfc06a5dee10f830ef243))
* add v4 branch protections ([d17416d](https://github.com/gaima8-org/fork-terraform-github-repository/commit/d17416d499d863b82f86d5818bb30921859d77f9))
* Add visibility parameter and deprecate private parameter ([461d873](https://github.com/gaima8-org/fork-terraform-github-repository/commit/461d8735a862aafb44fa707c1ad21a848c99cb47))
* **boostsecurityio:** Github pages, web_commit_signoff_required, and terraform provider 6.x fixing pages ([#5](https://github.com/gaima8-org/fork-terraform-github-repository/issues/5)) ([44ac511](https://github.com/gaima8-org/fork-terraform-github-repository/commit/44ac51180a26023091ff975225f341e51a9cdaaa))
* **cutlery42:** Various updates ([#7](https://github.com/gaima8-org/fork-terraform-github-repository/issues/7)) ([035f478](https://github.com/gaima8-org/fork-terraform-github-repository/commit/035f4788abc91fbc0a81d3cb6bb7480fb1d137d1))
* Drop projects ([#9](https://github.com/gaima8-org/fork-terraform-github-repository/issues/9)) ([13c8f36](https://github.com/gaima8-org/fork-terraform-github-repository/commit/13c8f3630682f4718a4d9385335aae775235b306))
* Only support latest versions of Terraform and Official GitHub Terraform Provider ([bd02a29](https://github.com/gaima8-org/fork-terraform-github-repository/commit/bd02a29748403e952f8e890c6e84b89a72073466))
* Remove support for unsecure providers versions ([3c508a4](https://github.com/gaima8-org/fork-terraform-github-repository/commit/3c508a4d53aad749d478a2f3b1018324caa87544))
* Run tests with terraform 0.14.x ([fc9d73f](https://github.com/gaima8-org/fork-terraform-github-repository/commit/fc9d73ff02962af35dc9f4797c1ed87719f526f5))
* upgrade pre-commit hooks to v0.2.3 ([42615b7](https://github.com/gaima8-org/fork-terraform-github-repository/commit/42615b7cd978cefcb9b6e16d4fa154a93f4ceb58))
* Use 4.5 feature to directly assign teams via slug ([4c18823](https://github.com/gaima8-org/fork-terraform-github-repository/commit/4c18823d613d3d3c17148f0b475f0a5f134493bb))
* use github_branch_default resource to set default branch ([914d08a](https://github.com/gaima8-org/fork-terraform-github-repository/commit/914d08ae0b6faf03831aa65ffb3fc7871bf444e6))
* use official GitHub provider ([409a88e](https://github.com/gaima8-org/fork-terraform-github-repository/commit/409a88e85a753e550229fdd7024c265e2857ba62))
* use official GitHub provider ([fed1500](https://github.com/gaima8-org/fork-terraform-github-repository/commit/fed1500357f17ee1d1cdbbb55670617f86326b99))


### Bug Fixes

* add allow_auto_merge to resource ([b899f32](https://github.com/gaima8-org/fork-terraform-github-repository/commit/b899f32dbfd69fe15fde38fdb4139fe16360c277))
* allow for underscore in GitHub team slugs ([f1bfc4a](https://github.com/gaima8-org/fork-terraform-github-repository/commit/f1bfc4a2076e9dc903580d44c18a53ec1f0a0d51))
* always set correct value for vulnerability_alerts to avoid drifts ([f936748](https://github.com/gaima8-org/fork-terraform-github-repository/commit/f936748609db7f602bbd4dd30588e281d367054d))
* change repository link after repository relocated back to github ([a19e962](https://github.com/gaima8-org/fork-terraform-github-repository/commit/a19e962711307581b02bc2879f5c275456d538d5))
* changelog ([a643209](https://github.com/gaima8-org/fork-terraform-github-repository/commit/a643209cb3f0190e05d838097dae5ca1b0187f9d))
* changelog ([0037dba](https://github.com/gaima8-org/fork-terraform-github-repository/commit/0037dbab3c98a776048587a833706e885bbac641))
* fix wrong default value ([e9ea3f1](https://github.com/gaima8-org/fork-terraform-github-repository/commit/e9ea3f178ce5de34d7deb95bc8080b8d1e8bae95))
* fix wrong variable default ([7b65595](https://github.com/gaima8-org/fork-terraform-github-repository/commit/7b65595ac1db887b867509980bf91aafeea0773f))
* handling multiple branch protections with dependencies to teams ([fc0c278](https://github.com/gaima8-org/fork-terraform-github-repository/commit/fc0c278fee50e30e1cfdc31f3bffbff3c48488d2))
* handling multiple branch protections with dependencies to teams ([3316814](https://github.com/gaima8-org/fork-terraform-github-repository/commit/331681461de9deb097602bc11f239c85d01353ef))
* improve wording in docs ([5d0c0b3](https://github.com/gaima8-org/fork-terraform-github-repository/commit/5d0c0b3ce955c9b84793c00955f48a3afcb71831))
* mark webhooks output as sensitive ([8ab19b6](https://github.com/gaima8-org/fork-terraform-github-repository/commit/8ab19b658d155840af71466259124fdb487acd30))
* mask broken versions ([e87878b](https://github.com/gaima8-org/fork-terraform-github-repository/commit/e87878ba491a459247d5bcfd08583608adffedfe))
* provider version requirements ([deee1cb](https://github.com/gaima8-org/fork-terraform-github-repository/commit/deee1cb9d1eb69618e69d5007dd9c21263030bfc))
* remove doubled up brackets ([2d7f37e](https://github.com/gaima8-org/fork-terraform-github-repository/commit/2d7f37e90b599224e26918f0cb7223aae2315a22))
* remove projects test as disabled in test org ([9a4693a](https://github.com/gaima8-org/fork-terraform-github-repository/commit/9a4693a85802738bebd04b181798274e4352a68d))
* remove support for string list in branches variable ([ae84490](https://github.com/gaima8-org/fork-terraform-github-repository/commit/ae84490de9112e63f978e508e406f990111a64c7))
* Remove uneeded tests that actually only test provider and github api but not module ([d80a14e](https://github.com/gaima8-org/fork-terraform-github-repository/commit/d80a14e9dc8b6f3727fc0c356231e5ae6de74f3a))
* revert defaults to what they were previously ([1ba8870](https://github.com/gaima8-org/fork-terraform-github-repository/commit/1ba887006f10ec1942161136520baacd916a4393))
* review comments ([2969be6](https://github.com/gaima8-org/fork-terraform-github-repository/commit/2969be6feb91e25c76ee8ab475e8bb874d1ebd44))
* use name instead of slug to make the example working again ([b7d71b8](https://github.com/gaima8-org/fork-terraform-github-repository/commit/b7d71b80014802b79780b0af09f28069bf1c3dea))
* Validate 'pages' is defined correctly. ([#8](https://github.com/gaima8-org/fork-terraform-github-repository/issues/8)) ([7a87fc2](https://github.com/gaima8-org/fork-terraform-github-repository/commit/7a87fc24e4b44a7cffcc00ee0c25e6d57781e1f7))
* var.app_installations should be of type set(string) instead of set(number) ([5a2dad9](https://github.com/gaima8-org/fork-terraform-github-repository/commit/5a2dad9cb4d36907f969db975e8c7cdb9c65e087))


### Code Refactoring

* allow computed values in v4 branch protections ([31c2492](https://github.com/gaima8-org/fork-terraform-github-repository/commit/31c249296176b08b59f607b2fc15557bb502312e))

## [Unreleased]

## [0.19.1]

### Changed

  JonathanSerafini: update for terraform provider 6.x fixing pages
  JonathanSerafini: add web_commit_signoff_required

## [0.19.0]

### Changed

- BREAKING: update to provider `>= 4.31` for supporting default squash and merge commit titles and messages

### Added

- Add support for `squash_merge_commit_title`
- Add support for `squash_merge_commit_message`
- Add support for `merge_commit_title`
- Add support for `merge_commit_message`

## [0.18.0]

### Added

- Add support for v4 branch protections.

### Removed

- BREAKING CHANGE: Remove deprectated variable `branch_protections` please use `branch_protections_v3` instead.

### Deprecated

- Mark `var.defaults` as deprecated. This variable was introduced and used before Terraform Module `for_each` was available.

## [0.17.0]

### Added

- Add support for Terraform GitHub Provider version `5.x`

## [0.16.2]

### Fixed

- `var.app_installations` should be a of type `set(string)` instead of `set(number)`

## [0.16.1]

### Added

- Add support for `github_app_installation_repository`

## [0.16.0]

### Fixed

- Set correct default value for `delete_branch_on_merge` in docs
- BREAKING CHANGE: Remove support for multi-type variable `branches` (removed `list(string)` support)

## [0.15.0]

### Fixed

- Set correct alternative type for `deploy_keys` in README

### Added

- Add support for `github_branches`

## [0.14.0]

### Added

- Add support for `require_conversation_resolution` for Branch Protection (thanks to @0x46616c6b)
- Add support for `encrypted_secrets`

### Changed

- BREAKING: update to provider `~> 4.20` fixing an issue that was just supporting `v4.19.x`

## [0.13.0]

### Added

- Add GitHub Autolink References configuration block (thanks to @0x46616c6b)

## [0.12.0]

### BREAKING CHANGES

Bumped the minimum supported version of the GitHub Terraform Provider to `v4.19.2`
since it contains a critical bugfix to support `required_approving_review_count = 0`
on branch protection rules. Also, `allow_auto_merge` has been added in `v4.17.0`.

### Added

- Add support for `allow_auto_merge`

## [0.11.0]

### BREAKING CHANGES

We dropped support for Terraform pre 1.0 and GitHub Terraform Provider pre 4.0.
In addition we changed to the `integrations/github` official GitHub Terraform Provider.
This needs migration actions if you already used this module with the `hashicorp/github` provider and want to upgrade.

#### Migration from previous versions

To migrate from a previous version, please ensure that you are using the
`integrations/github` official GitHub Terraform Provider.

```hcl
terraform {
  required_version = "~> 1.0"

  required_providers {
    github = {
      source  = "integrations/github"
      version = "~> 4.0"
    }
  }
}
```

Once you've updated the provider, a manual state migration is required to
migrate existing resources to the new provider.
The following command will replace the provider in the state.

```bash
terraform state replace-provider registry.terraform.io/hashicorp/github registry.terraform.io/integrations/github
```

After you've migrated the state, please run
`terraform init` to apply the changes to the resources.

### Added

- Add support for Official GitHub Terraform Provider `integrations/github`

### Removed

- Removed support for Terraform < 1.0
- Removed support for GitHub Provider < 4.0
- Removed compatibility to Hashicorp GitHub Terraform Provider `hashicorp/github`

### Fixed

- Set `webhooks` output as sensitive.
- Add underscores in team names (special thanks to @marc-sensenich)
- Fix `dismiss_stale_reviews` in README to a default value of `true`

## [0.10.1]

### Fixed

- Set `vulnerability_alerts` per default to `true` for public repositories and
  to `false` for private repositories if not explicitly set to avoid drifts
  when running `terraform plan`.

## [0.10.0]

### Added

- Add support for Terraform `v1.0`

## [0.9.2]

### Fixed

- Fix terraform typing issue when defining branch protections for multiple branches

## [0.9.1]

### Added

- Add support for GitHub Pages configuration in repositories

## [0.9.0]

### Added

- Add support for Terraform `v0.15`

## [0.8.0]

**_This is a BREAKING RELEASE._**

Branch protection resourcess will be recreated and new fetures are added enforcing security by default.

Please review plans and report regressions and issues asap so we can improve documentation for upgrading.

### Upgrade path/notes:

- Branch protections will be recreated in a compatible way. Alternatively, all branch protections could be manually updated using `terraform state mv` but this is not recommended as it is a manual process that can suffer from human prone errors.
- If you do not want to archive repositories on deletion set `archive_on_destroy` to false in repository configurations.

#### Expected differences in a plan after upgrading:

- Addition to `module.<NAME>.github_repository.repository`:
  - Addition or changed default of argument `archive_on_destroy = true`
- Destruction of `module.<NAME>.github_branch_protection.branch_protection[*]`
- Creation of `module.<NAME>.github_branch_protection_v3.branch_protection[*]`
- Replacement of `module.<NAME>.github_team_repository.team_repository_by_slug[<SLUG>]`
  - Triggered by change in `team_id = "<NUMBER>" -> "<SLUG>"`

### Added

- Add support for Github Provider v4 (Minimal compatible version is v4.5).
- Add support for `archive_on_destroy` repository flag defaulting to `true`.
- Add support for `vulnerability_alerts` repository flag.
- Add security deny list for v4.7.0, v4.8.0, v4.9.0 and v4.9.1 due to a bug setting visibility to public for templated repository creation.

### Changed

- Use [`github_branch_protection_v3`](https://registry.terraform.io/providers/integrations/github/latest/docs/resources/branch_protection_v3) instead of [`github_branch_protection`](https://registry.terraform.io/providers/integrations/github/latest/docs/resources/branch_protection) for performance and compatibility reasons. **ATTENTION**: This Change will trigger recreation of all branch protections when upgrading to v0.8.0.
- Use `github_branch_default` to set default branch of repositories. **ATTENTION**: This Change will trigger creation of new resource when `default_branch` argument is set.

### Removed

- **BREAKING CHANGE**: Removed support for Github Provider before v4.3

## [0.7.0]

### Added

- Add support for `visibility` parameter. Defaults to `private` and respects desired state as defined in deprecated `private` parameter.

### Changed

- Add deprecation of `private` parameter.
- **BREAKING CHANGE:** Minimum Github Terraform Provider version increased to `2.9.0`.

### Added

## [0.6.1]

- Add support for managing github secrets via `plaintext_secrets` argument (#58/#59 kudos to @mrodm)

## [0.6.0]

### Added

- Add support for Terraform v0.14.x

## [0.5.1]

### Fixed

- Remove support for Terraform Github Provider v3.1.0 as this version introduced undocumented breaking changes. See https://github.com/integrations/terraform-provider-github/issues/566 for details.

### Changed

- Adjust default branch in code to github new default branch naming

## [0.5.0]

### Added

- Add support for Terraform v0.13.x
- Add support for Terraform Github Provider v3.x
- Prepare support for Terraform v0.14.x (needs terraform v0.12.20 or above)

## [0.4.2] - 2020-06-23

### Added

- Add `CHANGELOG.md`.

### Changed

- Switch CI from SemaphoreCI to GitHub Actions.

## [0.4.1] - 2020-06-04

### Added

- Add CONTRIBUTING.md.
- Add `phony-targets` and `markdown-link-check` hooks.

### Changed

- Update logo and badges in README.md.

## [0.4.0] - 2020-05-28

### Fixed

- Fix a bug that was introduced during the last release which forced the
  re-creation of teams on every run.

## [0.3.1] - 2020-05-24

### Fixed

- Fix dependency issue when assigning teams by name.

## [0.3.0] - 2020-05-14

### Added

- Add `issue_labels_create` to specify whether you want to force or suppress the
  creation of issues labels. Default is `true` if `has_issues` is `true` or
  `issue_labels` is non-empty, otherwise default is `false`.

## [0.2.1] - 2020-05-09

### Added

- Introduced support for the
  [github_repository_webhook](https://www.terraform.io/docs/providers/github/r/repository_webhook.html)
  resource. You can now add webhooks to your repositories through the newly
  introduced variable `webhooks`. For further information please read the
  [documentation](https://github.com/mineiros-io/terraform-github-repository#webhooks-configuration).

## [0.2.0] - 2020-04-16

### Added

- Use slugs for team ids.

### Changed

- Set `delete_branch_on_merge` default value to `true`.
- Upgrade terraform-github-provider to `~> 2.6`.

### Fixed

- Fix module dependency by introducing `modules_depends_on`.

## [0.1.0] - 2020-02-27

### Changed

- Update README.md and add more examples and related tests.

## [0.0.7] - 2020-01-14

### Changed

- Breaking Changes for `branch_protection_rules`. Properties are now configured
  as a nested object instead of lists.

## [0.0.6] - 2020-01-12

### Changed

- Ignore changes in `auto_init`.
- Ignore changes in `gitignore_template`.
- Ignore changes in `license_template`.

## [0.0.5] - 2020-01-12

### Added

- Add `defaults`.
- Add `extra_topics` for adding additional topics when defaults.topics should
  not be overwritten but merged.
- Add `admin_collaborators` as a list of github usernames to add as
  collaborators with admin permission.
- Add `push_collaborators` as a list of github usernames to add as collaborators
  with push permission.
- Add `pull_collaborators` as a list of github usernames to add as collaborators
  with pull permission.
- Add `admin_team_ids` as a list of team IDs to add as admin teams.
- Add `push_team_ids` as a list of team IDs to add as push teams.
- Add `pull_team_ids` as a list of team IDs to add as pull teams.

### Changed

- Use `for_each` instead of `count` to not recreate most resources when order
  in module parameter changes.
- Add automated unit tests.

### Fixed

- Fix race condition in `branch_protection` configuration.

### Removed

- Remove `teams`.
- Remove `collaborators`.

## [0.0.4] - 2020-01-06

### Changed

- Set `auto_init` default value to `true`.

## [0.0.3] - 2020-01-06

### Changed

- Set `has_issues` default value to `false`.

## [0.0.2] - 2020-01-06

### Removed

- Remove unnecessary `Vars` declaration from test.

### Changed

- Set `has_feature` toggles default values to `false`.
- Set example variables default value to null.

## [0.0.1] - 2020-01-05

### Added

- This is the initial release of our GitHub Repository module with support for
  creating and managing GitHub Repositories for Organizations.

[unreleased]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.19.0...HEAD
[0.19.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.18.0...v0.19.0
[0.18.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.17.0...v0.18.0
[0.17.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.16.2...v0.17.0
[0.16.2]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.16.1...v0.16.2
[0.16.1]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.16.0...v0.16.1
[0.16.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.15.0...v0.16.0
[0.15.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.14.0...v0.15.0
[0.14.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.13.0...v0.14.0
[0.13.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.12.0...v0.13.0
[0.12.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.11.0...v0.12.0
[0.11.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.10.1...v0.11.0
[0.10.1]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.10.0...v0.10.1
[0.10.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.9.2...v0.10.0
[0.9.2]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.9.1...v0.9.2
[0.9.1]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.9.0...v0.9.1
[0.9.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.8.0...v0.9.0
[0.8.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.7.0...v0.8.0
[0.7.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.6.1...v0.7.0
[0.6.1]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.6.0...v0.6.1
[0.6.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.5.1...v0.6.0
[0.5.1]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.5.0...v0.5.1
[0.5.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.4.2...v0.5.0
[0.4.2]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.4.1...v0.4.2
[0.4.1]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.4.0...v0.4.1
[0.4.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.3.1...v0.4.0
[0.3.1]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.2.1...v0.3.0
[0.2.1]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.0.7...v0.1.0
[0.0.7]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.0.6...v0.0.7
[0.0.6]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.0.5...v0.0.6
[0.0.5]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.0.4...v0.0.5
[0.0.4]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.0.3...v0.0.4
[0.0.3]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.0.2...v0.0.3
[0.0.2]: https://github.com/mineiros-io/terraform-github-repository/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/mineiros-io/terraform-aws-s3-bucket/releases/tag/v0.0.1
