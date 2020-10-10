# Public Bugbounty Programs

[![License](https://img.shields.io/badge/license-MIT-_red.svg)](https://opensource.org/licenses/MIT)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/projectdiscovery/public-bugbounty-programs/issues)
[![Follow on Twitter](https://img.shields.io/twitter/follow/pdchaos.svg?logo=twitter)](https://twitter.com/pdchaos)
[![Chat on Discord](https://img.shields.io/discord/695645237418131507.svg?logo=discord)](https://discord.gg/KECAGdH)

This is a source for programs available on [chaos.projectdiscovery.io](http://chaos.projectdiscovery.io/). Please send pull-request of public bug bounty programs that you want to include in our public list with recon data. 

We are currently accepting in JSON format, an example is below:

```json
{
   "name":"HackerOne",
   "url":"https://hackerone.com/security",
   "bounty":true,
   "domains":[
      "hackerone.com",
      "hackerone.net",
      "hacker101.com",
      "hackerone-ext-content.com"
   ]
}
```

**Important notes:** 
- Our backend only accepts TLD as input in the `domains` field, so please do not add subdomains or URLs in `domain` field. 
- Use JSON validators (e.g. [jsonlint](https://jsonlint.com) to validate the modified `chaos-bugbounty-list.json` file when sending pull requests.

Thanks again for your contribution and keeping the community vibrant. :heart:

-------

If you want to remove any program from the list, please contact us at contact@projectdiscovery.io.

## Resources

- https://github.com/arkadiyt/bounty-targets-data
- https://github.com/disclose/disclose/tree/master/program-list
