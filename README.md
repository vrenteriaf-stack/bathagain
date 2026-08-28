# Clean home URL

Four files. Upload to the repo ROOT (`https://github.com/vrenteriaf-stack/bathagain/upload/main`)
and commit — GitHub will replace the existing copies.

Every link that pointed at `index.html` now points at `/`, so clicking HOME or the logo
lands on `bathagain.com` instead of `bathagain.com/index.html`. Sixteen links in total:
the logo, the HOME item in the desktop nav, the HOME item in the mobile menu, and Home in
the footer, on each of the four pages.

Nothing else changed.

## Note on the other pages

The inner pages still read `bathagain.com/About.dc.html`. Hiding those extensions means
restructuring each page into its own folder (`/about/index.html`, and so on) and updating
every internal link. Worth doing, but it is a bigger change and would also break any link
already shared. Say the word if you want it.
