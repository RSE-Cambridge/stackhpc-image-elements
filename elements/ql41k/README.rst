=========
ql41k
=========
Install QL41K RPMs from a local repo using ``yum``.

* ``DIB_QL41K_REPO`` Define a URL for the QL41K package repo.
  This is the directory containing the RPMS/ subdirectory.
  e.g. https://cumulus-repo.vss.cloud.cam.ac.uk/ql41k
       http://128-232-192-150.vss.cloud.cam.ac.uk/ql41k

* ``DIB_QL41K_VERSION`` Define a version for the QL41K release.
  This is used in the Yum repo name.
  e.g. 8.37.30.0-1.rhel7u6.x86_64

* ``DIB_QL41K_PKGLIST`` Define a space-separated list of packages to install.
  Default is ``kmod-qlgc-fastlinq-8.37.30.0-1.rhel7u6.x86_64``

* ``DIB_QL41K_DELETE_REPO`` Delete the repo after building the image.
  Default is ``y``
