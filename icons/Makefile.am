iconsdir = $(pluginiconsdir)/scalable/apps
icons_DATA =				\
	plugin-earth.svg		\
	plugin-throw.svg		\
	plugin-animationplus.svg	\
	plugin-animationsim.svg

install-data-hook:
	$(shell which gtk-update-icon-cache &> /dev/null &&	\
	gtk-update-icon-cache -f -t $(pluginiconsdir))
