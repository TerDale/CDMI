This repository is based on the CDMI Reference Implementation, version
1.0e as supplied by SNIA.  All files here are available under the same
license that SNIA uses.  See LICENSE.txt for the details.

The files CDMI_RI.pdf, ReleaseNotes.txt and README.txt come from SNIA.
They provide, respectively, a technical description of the reference
implementation, the SNIA-supplied release notes for this release and
general information about CDMI.

The layout of the files have been changed, both to match the standard
maven layout and to suite our needs.  The project is split into two
modules: cdmi-core and cdmi-web.  The cdmi-core builds a jar file
containing the actual code and the cdmi-web modules builds a war file
suitable for direct deployment.

The version numbers have a '-dCache-' designator to distinguish them
from any jar files that others might publish.
