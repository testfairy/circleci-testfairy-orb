# circleci-testfairy-orb

How to publish a new version to CircleCI ORB

Setup
```
# brew install circleci (or curl -fLSs https://circle.ci/cli | bash if you're not a brew user)
# circleci setup (you'll have to go https://circleci.com/account/api to get an api token)
```

```
# circleci orb publish orb.yml testfairy/uploader@dev:1.0.0
# circleci orb publish promote testfairy/uploader@dev:1.0.0 major
```
