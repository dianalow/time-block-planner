# Generate Time-Block Planner Pages

Forked from [drewish](https://github.com/drewish/planner) for yet another take on Cal Newport's Time-Block Planner.

This version produces the planner in [Traveler's Company](https://www.travelers-company.com/)'s Traveler's Notebook Regular size.

## Installation

Assuming you've got [Ruby](http://www.ruby-lang.org/en/) and [Bundler](https://bundler.io)
installed you can just run:
```
git clone git@github.com:dianalow/time-block-planner.git
cd time-block-planner
bundle install
```

## Usage

It assumes you want to generate pages for the next week so there are no options:
```
./planner.rb
```

You can generate pages for a different weeks by passing in the date:
```
./planner.rb 2022-05-27
```

On a Mac you can send the PDF directly to your printer:
```
lpr time_block_pages.pdf
```

## Limitations

Probably only works on a Mac since it hardcodes the font path.
