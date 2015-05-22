## Week 3 - Assignment 4

### Description

This assignment serves to reinforce Ruby syntax and usage of blocks and enumerable with arrays and hashes. You'll also dabble in String manipulation.

After completing this assignment, you should:

* Understand using methods from `Enumerable` like: `map`, `select`, `reject`, `max_by` and `sort`.
* Understand using related methods on `Array` like: `uniq` and `each`.
* Understand using useful methods on `String` like: `split`, `lines` and `gsub`.
* Be able to use existing tests to very your code is working correctly.
* be able to effectively use tools like `observr` to automatically run your tests.

### Details

* - [ ] Fork this [Green Eggs and Ham](https://github.com/tiy-tpa-rails-q2-2015/green_eggs_and_ham) repository.
* - [ ] Clone your forked repo to your computer.
* - [ ] `cd` into your cloned repo, `bundle install` and run `observr test/observr` to get started.
* - [ ] As you get each test passing, remove the line `skip` from the next test.
* - [ ] Complete the first five tests in `test/test_green_eggs_and_ham.rb`.

### Bonus

* - [ ] Complete the last two tests. Their solutions are very simple, but might be a little tricky to figure out.

### Hints

The some of the tests expect words to be lowercase, but not all of the words in the text are lower case. Some of the words also end in punctuation that should be excluded when checking for unique words, i.e. "Sam-I-am!", "Sam-I-am", and "sam-i-am" should all be considered the same word.

Here's how to normalize them:

```ruby
word = "Sam-I-am!"
word.downcase.gsub(/[^a-z-]/, '') # => "sam-i-am"
```

We'll talk about Regular Expressions soon, that's what the `/[^a-z-]/` is (it matches all characters that are not "a" through "z" or "-"). Feel free to research if you want, but this is a freebie.

### Resources

* http://ruby-doc.org/core-2.2.2/Enumerable.html
* http://ruby-doc.org/core-2.2.2/Array.html
* http://ruby-doc.org/core-2.2.2/String.html
