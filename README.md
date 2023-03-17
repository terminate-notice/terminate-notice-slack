# Terminate Notice - slack

___Handle your AWS Spot Instance Actions with terminate-notice___

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

## Installing

On Debian or RedHat based systems, get the 
[latest version of the package](https://github.com/terminate-notice/terminate-notice/releases/latest)
and install it. You will also need the
[latest version of this package too](https://github.com/terminate-notice/terminate-notice-slack/releases/latest).

Check all your settings are OK in the folder `/etc/terminate-notice.conf.d`
and then start the service with
`systemctl enable --now terminate-notice.service`. If the service is already
running, run `systemctl restart terminate-notice.service`.

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://jon.sprig.gs/"><img src="https://avatars.githubusercontent.com/u/228671?v=4?s=100" width="100px;" alt="Jon "The Nice Guy" Spriggs"/><br /><sub><b>Jon "The Nice Guy" Spriggs</b></sub></a><br /><a href="https://github.com/terminate-notice/YOUR_REPO/commits?author=JonTheNiceGuy" title="Code">💻</a></td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td align="center" size="13px" colspan="7">
        <img src="https://raw.githubusercontent.com/all-contributors/all-contributors-cli/1b8533af435da9854653492b1327a23a4dbd0a10/assets/logo-small.svg">
          <a href="https://all-contributors.js.org/docs/en/bot/usage">Add your contributions</a>
        </img>
      </td>
    </tr>
  </tfoot>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!