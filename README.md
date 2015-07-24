# branding
Brand all the things!

This branch is for the development and original source of the publicly-served
branding assets for Brobotic.

## Folder Structure

Here, everything is organized by *project* with sub-folders below for the many
*types* of content. Below is an example of the folder structure.

  * `brobotic`
    * `css`
    * `images`
    * `fonts`
  * `klobbe`
    * `css`
    * `images`
    * `fonts`
  * ...

## Other READMEs

Since each project is its own separate little thing, each one is free to use a
different toolchain or go about the management of its assets in whatever way
seems to make the most sense for that project. They are free to draw upon the
general `brobotic` project for the basic branding and studio brand assets and
should use the existing assets in production from that project rather than
copying them into their own to ensure a single point of control over the studio
brand. Projects are also free to build upon the base styling provided by the
`brobotic` project as well, as specified by the branding guide. Because of all
this, an additional README is encouraged in each project's subdirectory to
explain the particulars of how each project is dealing with the development of
their assets/overrides, as well as their organization.

## Branding Guide

Haven't actually written it yet, but it will be authoritative and we will put
information about it here when that gets written.

## Publishing Final Assets

When something is clear for publishing as an actual, usable asset in production,
it simply needs to be copied into the proper location on the `gh-pages` branch
in this repository and it will then be available on that path under the domain
`branding.brobotic.com` within a few minutes after pushing the branch.
