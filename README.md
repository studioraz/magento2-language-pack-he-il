# Hebrew language pack for Core Magento and 3rd party modules

## Included module:
- Amasty_Acart
- Amasty_Affiliate
- Amasty_Cart
- Amasty_Checkout
- Amasty_Extrafee
- Amasty_Gdpr
- Amasty_GiftCard
- Amasty_GiftWrap
- Amasty_Promo (Free Gift)
- Amasty_ShopbyBrand
- Amasty_SocialLogin
- Amasty_Sorting
- Amasty_StoreCredit
- Amasty_Xnotif (Out of Stock Notification)
- Magento_Checkout
- Magento_Customer
- Magento_SalesRule
- Magento_Tax
- Magento_Ui
- Mirasvit_Gdpr
- Mirasvit_Helpdesk
- Mirasvit_RewardPoints
- Mirasvit_SearchAutocomplete
- ParadoxLabs_Subscriptions
- Ubertheme_UbMegaMenu

## Install & update via composer steps 
1. `composer.phar require studioraz/magento2-language-pack-he-il`

## Releases

Releases follow the [shared Release Please guide](https://github.com/studioraz/ci-templates/blob/master/docs/release-please.md).
Use Conventional Commit PR titles (`feat: add support`, `fix: correct behavior`).
Squash merges use the PR title and body; single-commit PRs must have a matching commit title.

Pushes to `master`, the Monday 06:00 UTC schedule and manual runs maintain the release PR
and synchronize shared configuration.
Merging a release PR creates a GitHub Release and an unprefixed SemVer tag,
and updates the root `CHANGELOG.md`.

Enrollment preserves existing release history (verified baseline `2.0.5`).

The optional `RELEASE_TOKEN` is forwarded to the shared workflow. Without it,
`GITHUB_TOKEN` is used and bot-created PRs do not trigger PR-title CI. Supply a PAT or
GitHub App token when those checks are required.
