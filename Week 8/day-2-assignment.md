# Week 8 - Assignment 2

## Blog Donations

We're going to get started working with payment providers. Before we build a full fledged commerce app this weekend, lets try just taking a small fixed donation on our blog.

We'll use (Stripe's Checkout)[https://stripe.com/checkout] system to do this.

### Requirements

- [ ] Read the documentation for (Stripe Checkout)[https://stripe.com/docs/checkout].
- [ ] Sign up for a Stripe account and get your API keys.
- [ ] Use your .env file to store your keys locally as `PUBLISHABLE_KEY` and `SECRET_KEY`
- [ ] Pick a fixed amount, say $5 for the donations.
- [ ] Add a donation button for that amount to your blog app. Maybe in a sidebar or in the footer.
- [ ] Checkout the (Rails tutorial)[https://stripe.com/docs/checkout/guides/rails]. It should get you the rest of the way.
- [ ] There's something bugging me in the tutorial with the routes and their controller, see if you can tell what it is. Leave your guess as a comment on this issue.
- [ ] Even though the credit card details never hit our page, users will expect to see SSL in the browser when they make a credit card payment. Set your Rails app up to enforce SSL (in production only, setting it up in development is non-trivial). SSL works on your Heroku domains out of the box.
- [ ] Deploy your changes to Heroku.
- [ ] **Bonus**: Allow the user to choose how much they want to donate instead of a fixed amount.
