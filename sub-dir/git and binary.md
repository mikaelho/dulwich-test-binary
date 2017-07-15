Thanks.

Steps to recreate:

1. Create a new repository in github, with a README file.
2. Create a local directory and clone the new repository.
3. Modify README file and push - successful.
4. Create a new text file and push - successful.
5. Add a binary file in the root directory and push - successful.
6. Add a text file in a sundirectory and push - successful.

This has failed consistently with all image files, but here's the one used in latest test.

Above using the latest selfupdated version of stash:

    StaSh v0.6.18
    Pythonista 3.1 (301016)
    iOS 10.3.2 (64-bit iPhone8,2)
    root: ~/Documents/site-packages/stash
    stash.py: 2017-04-19 11:36:33
    SELFUPDATE_BRANCH: master
    BIN_PATH:
      ~/Documents/bin
      ~/Documents/stash_extensions/bin
      ~/Documents/site-packages/stash/bin
