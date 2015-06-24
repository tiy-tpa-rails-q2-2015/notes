# Week 7 - Assignment 4

## Microblogging Social Network (aka Twitter Clone)

### Objectives

#### Learning Objectives

After completing this assignment, you should…

* Understand using gems and their place in Rails development
* Understand Relationships between models
* Understand Personalization
* Understand Authentication
* Understand Pagination

#### Performance Objectives

After completing this assignment, you be able to effectively use

* authentication, sessions, and `current_user` with Devise
* Bootstrap
* Pagination with `kaminari`
* Validations
* Controllers
* Routes
* Models with `ActiveRecord`

### Details


- [ ] Users can signup, and sign in
- [ ] User can follow other users
- [ ] User can see posts from (themselves and people they follow) in their Timeline
- [ ] User can Post posts
- [ ] User can unfollow a person
- [ ] User can upload a profile picture (avatar)
- [ ] User's avatar should be desplayed everywhere that it makes sense
- [ ] Site should look nice
- [ ] Posts should be paginated
- [ ] Data should be seeded (look into `faker` and alternatives)
- [ ] Deploy to Heroku
- [ ] User can view a profile (/users/jwo)
- **Bonus**
  - [ ] Search posts
  - [ ] Users can block other users

### Notes

* Call your app something other than "Twitter"
* When logged in, the root URL should show the messages from all the people you follow.
* People can post "messages," "cheeps," or whatever you want to call them. They're tweets, but please don't call them that.
* Getting the list of messages for You + people you follow is tricky'ish. Think of it like this:

```ruby
class Post
  def self.timeline(user)
    follower_ids = user.followers.map(&:id)
    all_ids= follower_ids << user.id
    Post.where(user_id: all_ids).order("created_at DESC")
  end
end
```

...or perhaps a User automatically follows themeselves when creating their account?
