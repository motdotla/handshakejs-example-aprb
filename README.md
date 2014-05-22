# handshakejs-example-aprb 

Example of using [handshakejs-script](https://github.com/handshakejs/handshakejs-script) with a ruby Sinatra app for purpose of [Abril Ruby Conference](http://abrilproruby.com).

## Usage

Create an account at <http://handshakejs-signup.herokuapp.com/>.

```bash
git clone https://github.com/scottmotte/handshakejs-example-aprb.git
cd handshakejs-example-aprb
cp .example.env .env
```

Edit the contents of .env, then run the following.

```
bundle
bundle exec foreman start
```

Visit [http://localhost:5000](http://localhost:5000) in your browser.

## Deploying to Heroku

Create an account at <http://handshakejs-signup.herokuapp.com/>.

```bash
git clone https://github.com/scottmotte/handshakejs-example-aprb.git
cd handshakejs-example-ruby
heroku create
heroku config:set SALT=your_salt
heroku config:set APP_NAME=your_app_name
git push heroku master
```
