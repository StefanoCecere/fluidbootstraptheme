Fluid Theme for Twitter Bootstrap
============================================

[![Build Status](https://travis-ci.org/FluidTYPO3/fluidcontent_bootstrap.png?branch=master)](https://travis-ci.org/FluidTYPO3/fluidcontent_bootstrap)

## What is it?

A collection of Twitter Boostrap oriented Fluid Content Elements and Page Templates written for `EXT:fluidcontent` and `EXT:fluidpages` using ViewHelpers from `EXT:vhs`.
It uses `EXT:flux`

## What does it do?

Provides the template files and TypoScript setup necessary to use the included elements and pages.

## How does it do it?

By leveraging the integration logic provided by `EXT:fluidcontent` and `EXT:fluidpages` - enabling use of specially constructed Fluid templates as
content elements, much like the Flexible Content Elements concept from TemplaVoila.

## How is it installed?

Download, install the extension and include the static TypoScript configuration.

## How is it used?

After installation and inclusion of the static TypoScript, the included content elements and will be available as new content element
types and page layouts when inserting new content or creating new pages.

When inserted, each content element contains a special panel with configuration specifying how to render the content element. So do the pages.
After installation and inclusion of the static TypoScript configuration, a new group of templates is added to the page template
selection boxes in page properties - configurable with a page template to use for all subpages, just like TemplaVoila.


## References

* https://github.com/FluidTYPO3/fluidcontent is a dependency - it is the integration necessary to render Fluid Content Elements
* https://github.com/FluidTYPO3/fluidpages is a dependency - it is the integration necessary to render Fluid Page Templates
* https://github.com/FluidTYPO3/vhs is dependency providing many ViewHelpers used in the Fluid Content Element and Page templates
* https://github.com/FluidTYPO3/flux is a dependency and is used to configure how the content template variable are defined.