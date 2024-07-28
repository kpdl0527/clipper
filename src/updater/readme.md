# what
updater is planned feature to make it easier for users to update their yt_clipper install to the latest one

# how
the idea initial idea is to have a dedicated `updater` executable that will
    - query the `releases.json`
    - compare the version numbers of user's installed version to the latest version
        - the latest version id the first entry or index `0` of the `realeases.json` file
    - if the user's installed version is older, update