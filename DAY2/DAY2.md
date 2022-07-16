#  Date: 07-07-2022 (DAY 2)
​
## Summary of the steps to create a spec in ruby:

1. Create a project using bundler
2. Edit README.md 
3. Run 
` bundle install `
4. Solve the the errors of the boiler plate code (mentioned in bundle install)
5. Run
` bundle exec rspec `
6. Initialise the project and commit first time
7. Introducing a spec for necessary entity (Create a directory under spec and lib folder)
8. Create specs in spec folder. Similarly for the given specs create file in lib folder.
9. Example spec:
### point_sepc.rb:
​
```
RSpec.describe Geometry::Point do
  context "When testing Point Entity" do
    it "it should be initialised with two coordinates x,y" do
      expect {Geometry::Point.new(1,2)}.not_to raise_error
    end
  end
end
```
​
10. Add the requirement 
Example: 
```
require "line/point"
```
​
11. Creating an entity ruby(.rb) file:
Example:
```
module Line
  class Point
    def initialize(x,y)
    end
  end
end
```

---
---

## Additions to be done to MAC setup:

1. Iterm2
2. zsh to be used
3. git plug-in( create Alias)
4. Hot key(To open iterm)
5. Aligners(For your code)
​
---
---

## Books recommended:

1. Clean Code
2. TDD
3. Refactoring
4. Goal
​
---
---
​
​We continued the geometry problem( [Source code](https://github.com/maryada6/geometry) )

Weekend assignment: [Conways game of life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)( [Source code](https://github.com/maryada6/game-of-life) )

---
---
Apart from this we followed our time table and did code cycles, typing and speaking drills.

---
---
