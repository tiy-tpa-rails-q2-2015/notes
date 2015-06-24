# Week 7 - Assignment 1

## Image Uploads

You're going to add image attachements to your blog app we've been working on. You can use [CarrierWave](https://github.com/carrierwaveuploader/carrierwave/tree/v0.10.0), [Paperclip](https://github.com/thoughtbot/paperclip), whatever you want.

Your blog posts should be accompanied by a large image on it's main page, and a smaller
thumbnail on the index page. Consider also trimming the post on the index page to just
the first paragraph of the blog post on the second page.

You'll need to install [ImageMagick](http://www.imagemagick.org) on your Mac (probably via `homebrew`). You'll
also probably need RMagick or MiniMagick in your Rails app (I prefer MiniMagick). Heroku will already
have ImageMagick installed.

You'll also need to sign up for [AWS](http://aws.amazon.com) and create some S3 buckets (for development
and production).

## Requirement


- [ ] Your `Post` model should be extended to have a single image attachment.
- [ ] Your protected posts controller and views should be extended to allow uploading that image.
- [ ] That image attachment should be resized to a default size that works with your layout.
- [ ] You should also create a smaller thumbnail version of that image to use on your index page.
- [ ] Use S3 to store your file attachements in production (and optionally development, I recommend doing it in both).
- [ ] **Bonus**: After getting the above working, further modify your app to allow a `Post` to have _multiple_ images.