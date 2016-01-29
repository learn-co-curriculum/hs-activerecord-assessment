# ActiveRecord Costume Store

## Objectives

![jack o lantern emoji](http://www.emoji-cheat-sheet.com/graphics/emojis/jack_o_lantern.png) ![dog ghost emoji](http://www.emoji-cheat-sheet.com/graphics/emojis/ghost.png) ![jack o lantern emoji](http://www.emoji-cheat-sheet.com/graphics/emojis/jack_o_lantern.png)

For this morning's todo, you'll be creating the following tables: 'costumes','costume_stores', and 'haunted_houses'. You be creating the following classes: `Costume`, `CostumeStore`, and `HauntedHouse`. Each table will have three columns.

The `costumes` table will have:
  1. name
  2. price
  3. size

The `costume_stores` table will have:
  1. name
  2. location
  3. number of costumes, or "costume inventory"

The `haunted_houses` table will have:
  1. name
  2. location
  3. theme


## Instructions

#### File Structure

You will only be altering code in six files, the three files in the `models` folder and the three files in the `db/migrations` folder.

```
├── app
│   └── models
│       ├── costume.rb
│       ├── costume_store.rb
│       └── haunted_house.rb
└──db
    └── migrations
        ├── 001_create_costumes.rb
        ├── 002_create_costume_stores.rb
        └── 003_create_haunted_houses.rb
```

#### Getting Started

**This is a test-driven lab so start with the first test and work your way down.**

**Your models should be no longer than two lines of code.**

* The first step is to run `bundle install`.
* Create the Costume class in `app/models/`.
* Fill out the ActiveRecord migration for costumes such that it passes the specs.
* Create the CostumeStore class in `app/models/`.
* Fill out the ActiveRecord migration such that it `costume_stores` the specs.
* Create the HauntedHouse class in `app/models/`.
* Fill out the ActiveRecord migration for haunted_houses such that it passes the specs.
* Remember to run `rake db:migrate` every time you create a migration. 
* Just like for any other lab, run `rspec` to view your progress.

## Resources
* [ActiveRecord Migrations](http://guides.rubyonrails.org/migrations.html)
  * Just look at the code for the example migrations
* [Creating Active Record Models](http://guides.rubyonrails.org/active_record_basics.html#creating-active-record-models) 
* [Timestamps](http://api.rubyonrails.org/classes/ActiveRecord/Timestamp.html)

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/hs-activerecord-assessment' title='ActiveRecord Costume Store'>ActiveRecord Costume Store</a> on Learn.co and start learning to code for free.</p>
