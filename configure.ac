dnl   Copyright (C) 2013 Assaf Gordon <gordon@cshl.edu>
dnl
dnl   This file is free software; as a special exception the author gives
dnl   unlimited permission to copy and/or distribute it, with or without
dnl   modifications, as long as this notice is preserved.
dnl
dnl   This program is distributed in the hope that it will be useful, but
dnl   WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
dnl   implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

AC_INIT([gordon_bioinfo_bin_scripts],
        m4_esyscmd([config/git-version-gen .tarball-version]),
	[gordon@cshl.edu])

AC_CONFIG_AUX_DIR(config)
AM_INIT_AUTOMAKE([])
AC_CONFIG_MACRO_DIR([m4])

AC_SUBST(LICENSE,[AGPLv3-or-later])

AC_SUBST(VERSION)

AC_CONFIG_FILES( [
		  Makefile
		  scripts/Makefile
		  scripts/bam_to_bigwig
		  scripts/bam_to_genome_size
		  scripts/bam_to_genomecov_tabix
		  scripts/get_region_coverage
		  scripts/sam_to_bambai
		  scripts/revcomp
		  examples/Makefile
		  ] )

AC_OUTPUT()
