<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/readme_generator
It shall NOT be edited by hand.
-->

# Forgejo for YunoHost

[![Integration level](https://dash.yunohost.org/integration/forgejo.svg)](https://dash.yunohost.org/appci/app/forgejo) ![Working status](https://ci-apps.yunohost.org/ci/badges/forgejo.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/forgejo.maintain.svg)

[![Install Forgejo with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=forgejo)

*[Read this README is other languages.](./ALL_README.md)*

> *This package allows you to install Forgejo quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Forgejo is a self-hosted lightweight software forge. Easy to install and low maintenance, it just does the job.

Brought to you by an inclusive community under the umbrella of Codeberg e.V., a democratic non-profit organization, Forgejo can be trusted to be exclusively Free Software. It focuses on security, scaling, federation and privacy. 

### Features

- User dashboard, user profile and activity timeline.
- User, organization and repository management.
- Repository and organization webhooks, including Slack, Discord and Dingtalk.
- Repository Git hooks, deploy keys and Git LFS.
- Repository issues, pull requests, wiki, protected branches and collaboration.
- Migrate and mirror repositories with wiki from other code hosts.
- Web editor for quick editing repository files and wiki.
- Jupyter Notebook and PDF rendering.
- Authentication via SMTP, LDAP.
- Customize HTML templates, static files and many others.

**Shipped version:** 1.21.8-0~ynh1

## Screenshots

![Screenshot of Forgejo](./doc/screenshots/screenshot.png)

## Documentation and resources

- Official app website: <https://forgejo.org>
- Official user documentation: <https://forgejo.org/docs/latest/user/>
- Official admin documentation: <https://forgejo.org/docs/latest/admin/>
- Upstream app code repository: <https://codeberg.org/forgejo/forgejo>
- YunoHost Store: <https://apps.yunohost.org/app/forgejo>
- Report a bug: <https://github.com/YunoHost-Apps/forgejo_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/forgejo_ynh/tree/testing),


To try the testing branch, please proceed like that.

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/forgejo_ynh/tree/testing --debug
or
sudo yunohost app upgrade forgejo -u https://github.com/YunoHost-Apps/forgejo_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
