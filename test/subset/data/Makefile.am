# Process this file with automake to produce Makefile.in

NULL =
EXTRA_DIST =
CLEANFILES =
SUBDIRS = repack_tests

EXTRA_DIST += \
	$(TESTS) \
	expected/basics \
	expected/full-font \
	expected/cff-full-font \
	expected/japanese \
	expected/cff-japanese \
	expected/layout \
	expected/layout.gpos \
	expected/layout.gpos2 \
	expected/layout.gpos3 \
	expected/layout.gpos4 \
	expected/layout.gpos5 \
	expected/layout.gpos6 \
	expected/layout.gpos8 \
	expected/layout.gpos8.amiri \
	expected/layout.gpos9 \
	expected/layout.gsub3 \
	expected/layout.gsub5 \
	expected/layout.gsub6 \
	expected/layout.gsub8 \
	expected/layout.khmer \
	expected/layout.gdef \
	expected/layout.context \
	expected/layout.gdef-varstore \
	expected/layout.gdef-attachlist \
	expected/layout.notonastaliqurdu \
	expected/cmap \
	expected/cmap14 \
	expected/sbix \
	expected/colr \
	expected/cbdt \
	expected/variable \
	fonts \
	profiles \
	$(NULL)

# Convenience targets:
lib:
	@$(MAKE) $(AM_MAKEFLAGS) -C $(top_builddir)/src lib

TEST_EXTENSIONS = .tests
TESTS_LOG_COMPILER = $(srcdir)/../run-tests.py $(top_builddir)/util/hb-subset$(EXEEXT)
include Makefile.sources

-include $(top_srcdir)/git.mk
