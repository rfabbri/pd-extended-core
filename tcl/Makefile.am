AUTOMAKE_OPTIONS = foreign

SUFFIXES = .tcl

# we want these in the dist tarball
#EXTRA_DIST = CHANGELOG.txt notes.txt makefile.mingw


bin_SCRIPTS = pd-gui.tcl

libpdtcldir = $(pkglibdir)/tcl
dist_libpdtcl_SCRIPTS = pd-gui.tcl
dist_libpdtcl_DATA = apple_events.tcl dialog_canvas.tcl dialog_gatom.tcl dialog_path.tcl pd_bindings.tcl pd_menus.tcl pdwindow.tcl scrollboxwindow.tcl AppMain.tcl dialog_data.tcl dialog_iemgui.tcl dialog_startup.tcl pd_connect.tcl pdtk_array.tcl pkgIndex.tcl wheredoesthisgo.tcl dialog_array.tcl dialog_find.tcl dialog_message.tcl helpbrowser.tcl pdtk_canvas.tcl pkg_mkIndex.tcl dialog_audio.tcl dialog_font.tcl dialog_midi.tcl opt_parser.tcl pd_menucommands.tcl pdtk_text.tcl scrollbox.tcl pd_guiprefs.tcl pd.ico

ETAGS_ARGS = $(ETAGS) --language=none --regex="/proc[ \t]+\([^ \t]+\)/\1/" *.tcl

