# blog
Testing out a hugo build


# The big lesson
Really, Hugo is all about submodules

# Minutiae
The actual site is under "quickstart". Make new content/posts with `hugo new posts/my-post.md` . Themes are submodules, and the MAIN site is actually a submodule (!) under this repo(!) Submodules allow write access to the submodule (!)

hence, I can update the main site repo, using JUST this repo!
