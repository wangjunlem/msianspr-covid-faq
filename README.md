# [FAQ for Malaysians with SPR](https://wangjunlem.github.io/msianspr-covid-faq) <sub><sup><sub>(it's a link, click on it :D)</sub></sup></sub>
<br/>

**_Disclaimer:_**

_This document is meant for quick reference and is updated on a best effort basis. It may contain obsolete or incomplete information; as such, it should not be treated as the primary source of truth. We are not responsible for any mishaps/incidents that may occur as a result of any discrepancies in this document, including but not limited to the revocation of your SPR, additional costs for quarantine, and your failure to enter/exit either country._

---

This document contains information that is most relevant to Malaysian citizens with Singapore Permanent Residence (SPR) status who are not travelling under any official schemes.

If you find any errors (links not working, outdated information) in the document, please let me know (or do a pull request) and I'll rectify it as soon as I can. Segala kesulitan amat dikesali. 🤭

Take care and stay safe!

---

## Technical Details

This website is built speedily based on [GitHub Pages](https://pages.github.com/), which in turn supports [Jekyll](https://jekyllrb.com/) themes. The theme I have used is [bulma-clean-theme](https://github.com/chrisrhymes/bulma-clean-theme), which is built with the [Bulma](https://bulma.io/) framework.

In order to run this yourself or test any changes that you'll make, there are two methods:

### Remote (GitHub Pages)

This requires minimal set-up and is powered by GitHub's own system. You should fork this repo, and then set up GitHub Pages. Point it to your working branch. Any changes will be reflected on GitHub itself.

Please remember to do a Pull Request to merge your charges back into the [parent repo](https://github.com/wangjunlem/msianspr-covid-faq/).

### Local

This is more complex, and you will first have to set up Ruby and Jekyll. Documentation can be found [here](https://jekyllrb.com/docs/installation/). Subsequently, in the folder root, run `bundle install`.

You will then have to switch the commenting in `_config.yml` to use a locally-installed theme instead of the remote theme, like so:

```
theme: bulma-clean-theme
# remote_theme: wangjunlem/bulma-clean-theme
```

Then, use `bundle exec jekyll serve` in order to get your local up and running.