__NEXT STEP__
* Connect Google Authentication with local db.User :)

# auth-hbs-dash
Dashboard example using Passport Google OAuth 2.0, Handlebars

## Deployment
* [https://auth-hbs-dash.herokuapp.com/](https://auth-hbs-dash.herokuapp.com/) is automatically updated when the master branch on the repo is updated.
* Repo is at [https://github.com/KC135Q/auth-hbs-dash](https://github.com/KC135Q/auth-hbs-dash)

### Authentication
* Using PassportJS [passport-google-oauth20](http://www.passportjs.org/packages/passport-google-oauth20/) strategy.
* Go to [Google API Dashboard](https://console.developers.google.com/apis/credentials?project=zeta-flare-243220&authuser=1&folder&organizationId) to setup authorized domains (localhost and deployed application link), then add the `Authorized redirect URIs` such as `http://localhost:3000/auth/google/callback` and `https://auth-hbs-dash.herokuapp.com/auth/google/callback`

### Sequelize
* [Sequelize findOrCreate and findByPk](http://docs.sequelizejs.com/manual/models-usage.html)