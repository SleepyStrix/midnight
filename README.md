# Midnight

A library to parse natural language date/time into a cron expression.
This fork has been modified for use with midnight-js, found here: https://github.com/SleepyStrix/midnight-js

[![Build Status](https://travis-ci.org/bluefuton/midnight.svg?branch=master)](https://travis-ci.org/bluefuton/midnight)

## Installation

Install it yourself as:

	```
	gem install chronic
	gem install rake
	```
	
## Usage

<pre>Midnight.parse('every 5 minutes').to_s
 => "*/5 * * * *"</pre>

### Supported phrases

A full list of supported natural language phrases can be found in <a href="https://github.com/bluefuton/midnight/blob/master/test/test_parsing.rb">test_parsing.rb</a>.

In the future there'll be support for more complex repetitions - a wishlist can be found in <a href="https://github.com/bluefuton/midnight/blob/master/todo.txt">todo.txt</a>.

## Credits

My tokeniser code is based on the excellent <a href="https://github.com/yb66/tickle">Tickle</a> gem, which in turn relies on <a href="https://github.com/mojombo/chronic">Chronic</a> for date parsing.

Original Author: Chris Rosser <chris@bluefuton.com>


