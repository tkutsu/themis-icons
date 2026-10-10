# Themis Icons

A kitchen sink of monochrome icons from around the web, made for dark desktops.

## Install

Clone into your icon directory and pick `themis` as the icon theme:

```sh
git clone https://github.com/tkutsu/themis-icons ~/.local/share/icons/themis
gtk-update-icon-cache -f ~/.local/share/icons/themis
```

## Where the icons come from

Themis started as a merge of three monochrome sets and has been patched by hand since then. Most of the drawings belong to the people below.

- [Suru++ Asprómauros](https://github.com/suru-plus/suru-plus-aspromauros) by Gustavo Costa and Andrea Bonanni of the Suru++ Project is the base of the theme, and `index.theme` still carries its credits. Suru++ builds on Sam Hewitt's FreeDesktop Suru, which grew out of the original Suru by Matthieu James and the Canonical Design Team. It also borrows from [Papirus](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) by Alexey Varfolomeev, [La Capitaine](https://github.com/keeferrourke/la-capitaine-icon-theme) by Keefer Rourke, the [Numix](https://github.com/numixproject) mimetype icons, [Twemoji](https://github.com/twitter/twemoji) by Twitter, and Gravit Designer.
- [YAMIS](https://bitbucket.org/dirn-typo/yet-another-monochrome-icon-set) (Yet Another Monochrome Icon Set) by dirn fills in many app and tray icons.
- [Ghost Flat](https://www.gnome-look.org/content/show.php/Ghost+Flat?content=167256), a white set made for the HackStation theme, adds more. It was drawn from [ACYL](https://github.com/worron/ACYLS), originally by pobtott and later simplified by worron.
- [WhiteSur](https://github.com/vinceliuice/WhiteSur-icon-theme) by Vince Liu supplies the tray icons in `panel/` whose names end in `-osx`.

A few icons, such as `apps/16/eden.svg` and `panel/16/system-search-sf.svg`, were drawn for Themis.

## License

Themis is released under the GNU General Public License v3.0, the license of the sets it is built from. See [COPYING](COPYING) for the full text.
