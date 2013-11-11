Railscast sm-rc162
==================
Tree based navigation
```
Git clone
```
git clone https://github.com/sweetymehta/sm-rc162.git
```
Gemfile
```
gem 'ancestry' and bundle install
```
Form.html.erb
```
use collection_select to have parents in dropdown
take a parent_id for this
```
page.rb file
```
add attr_accessible :parent_id
has_ancestry
```
Refer this site for help
```
https://github.com/stefankroes/ancestry
```
In show.html.erb
```
show all roots 
@page.roots
show all childs
@page.children
show all ancestors with greaterthan sign
@page.ancestors &gt;
```
Rails server
```
rails s
```
Rails console
```
rails c
```



