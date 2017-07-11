gnome-shell.css:
	sassc tweaked1.scss gnome-shell.css

themedir=$(datadir)/themes/gnome-shell-theme-tweaked/gnome-shell
theme_DATA = \
	gnome-shell.css \
	theme/*.png \
	theme/*.svg

EXTRA_DIST = \
	theme/ \
	tweaked1.scss

uninstall-hook:
	-rmdir $(datadir)/themes/gnome-shell-theme-tweaked/gnome-shell
	-rmdir $(datadir)/themes/gnome-shell-theme-tweaked/

.PHONY: gnome-shell.css
