# The AngelAuraMC Wiki Repository

### Notice regarding the transition from PojavLauncherTeam to AngelAuraMC
The transition is still underway, and this wiki is a great example of the work to be done. Some links and information may errenously point to outdated or inaccurate results. 

### Notice for Amethyst users
Issues pertaining to Amethyst on [Android](https://github.com/AngelAuraMC/Amethyst-Android) or [iOS](https://github.com/AngelAuraMC/Amethyst-iOS) should be made in their respective repositories. They will be closed here, and repeat offenders will be blocked from this GitHub repository.

#### If you are/wish to be a Wiki Contributor, continue reading

The repository is using Vuepress V1, you can refer to [Vuepress Documentation](https://v1.vuepress.vuejs.org/) for more in-depth instruction.

The repository is structured like so
```
.
├── archived_pages
├── changelogs
└── markdown
    ├── .vuepress
    │    └── config
    ├── about
    ├── contribute
    ├── patchnotes
    └── wiki
        ├── faq
        │   ├── android
        │   └── ios
        ├── getting_started
        │   └── images
        │       └── INSTALL
        │           ├── android
        │           └── ios
        └── going_further
            └── images
                └── MODPACKS
                    ├── android
                    └── ios

```

* `archived_pages` - Contains pages that are no longer in use but we keep around for historical reasons.

* `changelogs` - An orphaned directory, pay no mind

* `markdown` - The 'root' directory of the wiki itself. The root directory is structured to be similar to how you see it on the URL.

* `.vuepress/config` - Contains the configuration files for the wiki itself. For most editing you need only edit `arrays.js`.


`arrays.js` is self-explanatory for the most part. The path in each section tells you where to put the corresponding `.md` files into as well as showing you examples on how to add your own page.

If you have any questions feel free to ask on the discord! [![Discord](https://img.shields.io/discord/724163890803638273.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.com/invite/5ptqkyZxEy) 


