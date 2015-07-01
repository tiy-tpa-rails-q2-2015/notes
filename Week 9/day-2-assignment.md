# Week 9 - Assignment 2

## Mixins and `ActiveSupport::Concern`

We're going to use `ActiveSupport::Concern` to create a mixin to alter the behavior of something in our app. E.g., you might extract the tagging functionality in your blog to be a generic `Taggable` concern that you could extract for use in another app (or even make into a gem/engine). "Mixins" like this help us reduce redundancies and organize code even if the concern is only used in one class.

Read about "composition over inheritance" and "single responsibility principle" for more on the _philosophical_ reasons we might do this.

- [ ] Pick any one of your apps you've worked on so far. E.g., your blog app, one of the weekend projects, etc.
- [ ] Use `ActiveSupport::Concern` in some way to define some functionality of one or more of your models.

### Resources

Here are some recommended reads on the subject:

* [Include vs Extend in Ruby](http://www.railstips.org/blog/archives/2009/05/15/include-vs-extend-in-ruby/) by John Nunemaker.
* [Code Concerns in Rails 4 Models](https://richonrails.com/articles/rails-4-code-concerns-in-active-record-models) blog post
* [`ActiveSupport::Concern` Documentation](http://api.rubyonrails.org/classes/ActiveSupport/Concern.html)
* []()
