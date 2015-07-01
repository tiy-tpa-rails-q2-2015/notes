# Week 9 - Assignment 3

## Technical Interview Practice and Thinking Like an Engineer

Write a algorithm which reverses the contents of an array in place. "In place" means we don't make a copy of the array, we modify it's contents, in place, one operation at a time. You'll only need (and can only use) built in ruby keywords, i.e. control structures (like loops), simple variable assignments, array element access and basic operators. You will not need (and should not call) any methods like `each`, `map`, `reverse`, etc.

**Tip**: It might help to cut out some paper squares and try to visual how you would perform the operations.

Here's some test boiler plate to get you started, you should only need to replace the comment `# YOUR SOLUTION HERE` with your code, operating directly on the array stored in `@ary` variable. You shouldn't need to change any other code.

```ruby
require 'minitest/autorun'

describe Array do
  before do
    @ary = %w(a b c d e)
  end

  it 'it can be reversed in place' do
    # YOUR SOLUTION HERE

    @ary.must_equal %w(e d c b a)
  end
end
```

Submit your solution in a gist.
