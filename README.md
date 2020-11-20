# [DEPRECATED] gettext-go
This project is no longer maintained. It has been deprecated in favour of [goi18n](https://github.com/ContextLogic/goi18n)

## Development
1. Make some changes, submit PR, and merge to master
2. Draft a new release here: https://github.com/ContextLogic/gettext-go/releases
3. Run `dep ensure -update github.com/ContextLogic/gettext-go` in customer repo (strings) and commit the resulting changes to `Gopkg.lock`. (You'll need to rebuild the docker container to get the updated package).
