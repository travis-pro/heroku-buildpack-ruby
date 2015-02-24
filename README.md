# DO NOT USE

We shoul not be using this buildpack any more. If you find an app using it, be sure to
add https://github.com/travis-ci/unlimited-jce-policy-jdk7 to `Gemfile`, remove
`$BUILDPACK_URL` from the Heroku app, and deploy.
