# WeakAuras 2

## [2.5.6-30-g17586f4](https://github.com/WeakAuras/WeakAuras2/tree/17586f4e1b6a34e3df9dc842ef53c790bfd711fa) (2018-02-24)

[Full Changelog](https://github.com/WeakAuras/WeakAuras2/compare/2.5.6...17586f4e1b6a34e3df9dc842ef53c790bfd711fa)

Benjamin Staneck (14):

- change some power types again
- change range check label from `Range` to `Distance`
- change back some power types as their format is not consistent
- change the global strings used for power type translations to be the ones of power types instead of the resource itself
- add some newlines to the changelog
- fix pkgmeta
- add the temp commit file to ,gitignore
- Update pkgmeta
- switch to manual changelog generation and add a script to do that
- only push localization if master changes and ignore the script in WowAce packaging
- add a script to automatically push translations to WowAce
- `dev` instead of `development`
- use the same version string for the window title as for the LDB tooltip
- fix LibRangecheck path

Infus (15):

- Fix cooldown handling of "disabled" cooldowns
- Remove a workaround for GetSpellCooldown("Water Jet")
- Reimplement Copy and Paste
- Options Window: Cooldown Progress: Fix initial value
- *** Add offset options to auras in dynamic groups
- Fix Range Check trigger
- Templates: Add KJ's burning wish to the correct specs
- Combat Log Trigger: Fix SPELL_ENERGIZE
- Add Allied Races to templates
- Attach legendaries/sets to each spec instead of a global list
- Update Templates based on suggestions from Nighthawk
- Add Range Checker trigger
- Transmission: Add a timeout if no data to check if we received data
- Add resizers to the bottom right corner
- Fix Stagger progress not updating

emptyrivers (1):

- implement UnitIsUnit option
