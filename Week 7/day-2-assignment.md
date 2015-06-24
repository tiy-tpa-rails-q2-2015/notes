# Week 7 - Assignment 2

## Using Third Party Authentication with oAuth

We're going to replace our hand-rolled user/password authentication in our Blog app with oAuth.

## Requirement

- [ ] You can use Devise or just use Omniauth by itself ([like we did in class](https://github.com/tiy-tpa-rails-q2-2015/banzai/commit/bfeac48d009489c8b208b0dfa8df3c1d954e08ab)). 
- [ ] Use Twitter, Github, Facebook, Google, whatever provider you want.
- [ ] Users should be able to sign in and out, just as before.
- [ ] Deploy your updated app to Heroku.
- [ ] **Bonus:** Restrict the users signing in to a predefined list of usernames/emails (ie. only you)
- [ ] **Bonus Bonus:** Allow the user to sign in with multiple providers, keeping tokens for all of them. You'll need to make a separate model to store the authorizations on, that belongs to your User (so you can have many of them).
