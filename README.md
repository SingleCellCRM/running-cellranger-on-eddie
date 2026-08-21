# Running CellRanger on Eddie

This lesson was developed from the template lesson that uses [The Carpentries Workbench][workbench]. 

## Description

Designed for staff and students at the University of Edinburgh, to be taught during Day Two of the IRR Bioinformatics Course hosted by the [IRR Single Cell & Spatial Biology Facility](https://regeneration-repair.ed.ac.uk/core-facilities/single-cell-spatial-biology) bioinformatics team.

During this course you will:

- Receive an introduction to [Eddie](https://www.wiki.ed.ac.uk/spaces/ResearchServices/pages/293580913/Eddie) (the University of Edinburgh's high-performance research computing cluster).
- Learn how to log in to an interactive node and staging node, navigate the university file system including your scratch space, and access datastore.
- Use university managed software via the Eddie module system.
- Download publicly available reference data.
- Set up a computing project folder.
- Write and submit a script to run CellRanger on 10X single-cell sequencing data.
- Copy the results to your personal computer and interpret the output.

## Requirements

To run this course, you will need:

- A personal laptop.
- A terminal window (Linux and Mac OS) or a ssh client such as [MobaXterm](https://mobaxterm.mobatek.net/) or [PuTTY](https://putty.org/index.html) (Windows).
- Your university staff or student username and password.
- To be connected to the university WiFi ([eduroam](https://information-services.ed.ac.uk/computing/desktop-personal/wifi-networking/configure-device)), or university [VPN](https://information-services.ed.ac.uk/computing/desktop-personal/vpn/vpn-service-using).
- To have completed Day One of the IRR Bioinformatics course.

## References

This course was developed using resources from:

- Data Carpentry
- HBC Training
- University of Edinburgh Research Services
- etc...

##

Follow the steps below to
complete the initial configuration of a new lesson repository built from this template:

1. **Make sure GitHub Pages is activated:**
   navigate to _Settings_,
   select _Pages_ from the left sidebar,
   and make sure that `gh-pages` is selected as the branch to build from.
   If no `gh-pages` branch is available, check the _Actions_ tab to see if the first
   website build workflows are still running.
   If they're not running yet, you may need to manually enable them via the _Actions_ tab.
   The branch should become available when those have completed.
1. **Adjust the `config.yaml` file:**
   this file contains global parameters for your lesson site.
   Individual fields within the file are documented with comments (beginning with `#`)
   At minimum, you should adjust all the fields marked 'FIXME':
   - `title`
   - `created`
   - `keywords`
   - `life_cycle` (the default, _pre-alpha_, is the appropriate for brand new lessons)
   - `contact`
1. **Annotate the repository** with site URL and topic tags:
   navigate back to the repository landing page and
   click on the gear wheel/cog icon (similar to ⚙️) 
   at the top-right of the _About_ box.
   Check the "Use your GitHub Pages website" option,
   and [add some keywords and other annotations to describe your lesson](https://cdh.carpentries.org/the-carpentries-incubator.html#topic-tags)
   in the _Topics_ field.
   At minimum, these should include:
   - `lesson`
   - the life cycle of the lesson (e.g. `pre-alpha`)
   - the human language the lesson is written in (e.g. `deutsch`)
1. **Adjust the 
   `CITATION.cff`, `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, and `LICENSE.md` files**
   as appropriate for your project.
   -  `CITATION.cff`:
      this file contains information that people can use to cite your lesson,
      for example if they publish their own work based on it.
      You should [update the CFF][cff-sandpaper-docs] now to include information about your lesson,
      and remember to return to it periodically, keeping it updated as your
      author list grows and other details become available or need to change.
      The [Citation File Format home page][cff-home] gives more information about the format,
      and the [`cffinit` webtool][cffinit] can be used to create new and update existing CFF files.
   -  `CODE_OF_CONDUCT.md`: 
      if you are using this template for a project outside The Carpentries,
      you should adjust this file to describe 
      who should be contacted with Code of Conduct reports,
      and how those reports will be handled.
   -  `CONTRIBUTING.md`:
      depending on the current state and maturity of your project,
      the contents of the template Contributing Guide may not be appropriate.
      You should adjust the file to help guide contributors on how best
      to get involved and make an impact on your lesson.
   -  `LICENSE.md`:
      in line with the terms of the CC-BY license,
      you should ensure that the copyright information 
      provided in the license file is accurate for your project.
1. **Update this README with 
   [relevant information about your lesson](https://carpentries.github.io/lesson-development-training/collaborating-newcomers.html#readme)**
   and delete this section.

[cff-home]: https://citation-file-format.github.io/
[cff-sandpaper-docs]:  https://carpentries.github.io/sandpaper-docs/editing.html#making-your-lesson-citable
[cffinit]: https://citation-file-format.github.io/cff-initializer-javascript/
[workbench]: https://carpentries.github.io/sandpaper-docs/
