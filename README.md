# VlinkCare
Monorepo GIT SUBMODULES POC for VLink(Beta)

Reasons for using a Mono-repo coding architecture:
-You want to be able to be able to treat two projects as separate yet still be able to use one from within another
-In a mono-lith, you will have to make sure every client has the shared library available
when making custom changes. Makes it difficult to merge when upstream changes become available
-Git submodules can solve this by allowing you to keep a Git repository as a subdirectory of another
Git repository.
-Git submodules let you clone another repository into your project and keep commits separate
