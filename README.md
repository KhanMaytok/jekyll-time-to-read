# Time to Read Plugin

A liquid filter for Jekyll 3.x and 4.x to indicate the time it takes to read an article.

## Installation

Copy `lib/jekyll-time-to-read.rb` to the `_plugins` directory of your Jekyll project, and restart Jekyll.


## Usage

Place the following tag somewhere within your layout:

`<p>Time to read: {{ content | reading_time_as_i }}</p>`

This generates the reading time as a number, like "4 minutes" or "less than 1 minute."

Alternatively, you can choose to render numbers less than 10 as a string:

`<p>Time to read: {{ content | reading_time_as_s }}</p>`

This generates the reading time similar to "four minutes" or "less than one minute."
