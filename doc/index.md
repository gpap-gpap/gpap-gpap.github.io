---
custom_page_title: "mantis geophysics"
exclude_h1: true
template: test.html
---

<div class="cover-container d-flex w-100 h-100 p-3 mx-auto flex-column">
<div class="col-md-9 col-sm-8 col-8">

# {{ page.custom_page_title }}
</div>
<div class="col-md-3 col-sm-4 col-4">
  <img alt="phasor"src="/{{ config.logo }}">
</div>
</div>

**mantis geophysics** is a University of Edinburgh spinout  created by researchers that have spent the last 10 years developing an innovative simulation approach to the geophysical demands associated with injection, that simplifies and accelerates the process of geophysically evaluating storage potentials. 

<div class="callout">

Our vision is to become the leading geophysical software and services company that offers the most sophisticated rock physics tools on the market, delivering full data potential and easy to use capabilities. 

</div>

## Why build another one?

Static website generators seem to be the favourite pastime of developers
procrastinating on other more important projects.
So of course, I needed to try making my own!
I also wanted to learn how to build command-line programs with [click][click]
and [Rich][rich], so this seemed the perfect side project.

## What Nēnē has to offer

Nēnē was designed to embody several features that I like from different static
site generators:

* **No-frills:** There are no fancy built-in templates, blogging support, RSS
  feeds, etc. You have to roll your own templates.
* **No assumptions about site layout:** The layout of the source files is the
  layout of the output HTML. Source files are converted to HTML, everything
  else is copied directly. It's that simple.
* **Templates have access to the entire content:** Not all generators allow any
  page to have access to the entire website content. This is great for building
  summary pages, lists of entries from across the site, etc.
* **Templates in Markdown files:** Using templating constructs in Markdown
  source files is extremely useful. I've only ever seen this in [Urubu][urubu].
* **Reads data from non-Markdown sources:** Most generators only allow data to
  come into templates from Markdown source files (body and YAML front matter).
  But sometimes data for building a page would be more natural coming from
  an external JSON/YAML/etc. [Eleventy][11ty] has this concept and now you can
  use it without first figuring out how to setup Nodejs.
* **Jupyter support:** Pages can be generated from
  [Jupyter notebooks][jupyter] (no execution) automatically.

## Free and open-source

Nēnē is free and open-source software distributed under the
[MIT License][license].

[nene-goose]: https://www.nps.gov/havo/learn/nature/nene.htm
[click]: https://github.com/pallets/click/
[rich]: https://github.com/willmcgugan/rich/
[urubu]: https://github.com/jandecaluwe/urubu
[11ty]: https://github.com/11ty/eleventy
[license]: https://github.com/leouieda/nene/blob/main/LICENSE.txt
[jupyter]: https://jupyter.org/
