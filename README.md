MVP Perks
---
A listing of tools & services freely available to Microsoft Most Valuable Professionals (MVPs) at [www.xavierdecoster.com/mvpperks](https://www.xavierdecoster.com/mvpperks/).

Note: Most of these offers are also available to Microsoft Regional Directors (MS RDs).

## How to Add a Perk
* Fork the repository
* Use the following [YAML](https://www.yaml.org/) template to create an additional perk.

```yml
  #name of the company & the uri to apply for an MVP license
- company: "Microsoft"
  uri: "https://mvp.microsoft.com/"
  #product/service description
  description: "MSDN Enterprise Subscription"
  #the products/services offered to MVPs
  products: ["Visual Studio", "Microsoft Azure Subscription"]
```
* Add the entry to the collection in `_data\perks.yml`.
* Submit a pull request

### Notes

* Try to use `{URL to Product/Service Page}` that points to information about what is needed to qualify for the MVP license.
* `products:` is a list of tools provided by the company like `Visual Studio` or `Microsoft Azure`.
  * If the company offers licenses to any tool of choice, enter `Any`.
  * Do not submit freeware or shareware to be listed, those aren't really *perks* :wink:
