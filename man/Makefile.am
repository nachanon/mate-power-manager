EXTRA_DIST =						\
	mate-power-manager.sgml			\
	mate-power-manager-bugreport.sgml	\
	mate-power-backlight-helper.sgml	\
	mate-power-statistics.sgml			\
	mate-power-preferences.sgml

if HAVE_DOCBOOK2MAN
man_MANS =						\
	mate-power-manager.1				\
	mate-power-manager-bugreport.1		\
	mate-power-backlight-helper.1		\
	mate-power-statistics.1			\
	mate-power-preferences.1
endif

if HAVE_DOCBOOK2MAN
mate-power-manager.1: mate-power-manager.sgml
	docbook2man $?

mate-power-manager-bugreport.1: mate-power-manager-bugreport.sgml
	docbook2man $?

mate-power-backlight-helper.1: mate-power-backlight-helper.sgml
	docbook2man $?

mate-power-preferences.1: mate-power-preferences.sgml
	docbook2man $?

mate-power-statistics.1: mate-power-statistics.sgml
	docbook2man $?
endif

clean-local :
	rm -f *~
	rm -f *.1
	rm -f manpage.*
