# c4g-blis-docs.github.io

## What this repo is for?
This is the Documentation Pages site for the [BLIS project](http://blis.cc.gatech.edu/). 

The [actual site](https://c4g-blis-docs.github.io/) serves as one single place for documentations regarding BLIS Tool.

Starting from Spring 2022, [BLIS workgroup](https://c4g-blis-docs.github.io/) decides to move all documentation regarding BLIS into one place for accessibility, maintainability and readability. In the current plan, this repo will includes following assets:

- [User Guide](/docs/index.md)
- [Frequently Asked Questions](/docs/faq.md)
- [Developer guide](/docs/developer_documentation/developer_guide_v0.1.md)

This webpage also allows you to conduct search through the docs.

## Contributing to this repo:

### Recommendation readings:
We are maintaining this webpage via [github page](https://pages.github.com/). Using [mkdocs](https://www.mkdocs.org/) to generate static sites from [markdown](https://en.wikipedia.org/wiki/Markdown) files under `/docs`. You can learn more from [this tutorial](https://squidfunk.github.io/mkdocs-material/publishing-your-site/).

### Develop & deploy steps:
If you are contributing to this repo, please follow the steps of:
- Add your documentations under /docs
- Before submitting, you can test the new changes offline running `mkdocs serve`. This will serve the site in your localhost. Default accessible at [port 8000](http://127.0.0.1:8000/).
- After merge into the main, you can run `mkdocs gh-deploy --force` under the main branch. This will deploy the changes to the actual github page website.