# Makefile.am for installation/src/config

desktop_DATA = release_notes.desktop
modconfigdir = $(prefix)/share/autoinstall/modules
modconfig_DATA = deploy_image.desktop

schemafilesdir =  $(schemadir)/autoyast/rnc
schemafiles_DATA = $(wildcard *.rnc)

EXTRA_DIST = $(desktop_DATA) $(modconfig_DATA) $(schemafiles_DATA)

include $(top_srcdir)/Makefile.am.common
