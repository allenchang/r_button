# rbutton
Get button input / simulate button trigger event


###====================================================================================
## How to write bb, download from Https
SUMMARY = "bitbake-layers recipe"
DESCRIPTION = "Recipe created by bitbake-layers"
LICENSE = "CLOSED"

SRC_URI = "https://github.com/allenchang/rbutton/archive/${PV}.tar.gz"


SRC_URI[md5sum] = "9ae578d32c72eebdb0f4b8c87b77ea6e"
SRC_URI[sha256sum] = "22ff260b2b3c47dea1d86eabc71b2036bf35f7a38cb756a121939974183e1151"

S = "${WORKDIR}/${PN}-${PV}"

inherit cmake

###====================================================================================
## How to write bb, download from git

SUMMARY = "bitbake-layers recipe"
DESCRIPTION = "Recipe created by bitbake-layers"
LICENSE = "CLOSED"

SRC_URI = "git://github.com/allenchang/rbutton.git;tag=${PV}" 

S = "${WORKDIR}/git"

inherit cmake
###====================================================================================