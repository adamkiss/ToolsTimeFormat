# TimeAgo for ProcessWire

This is a tiny ProcessWire Modules used for formatting times as 'X seconds ago', 'minutes ago'

## Usage

It's very simple. Load module, pass the timestamp to `format` function. Bam, done.

```
  $time_ago = $modules->get('ToolsTimeAgo');
  $posted = $time_ago->format($page->created);
```

## Credits

Created by [Adam Kiss](http://adamkiss.com) 2013  
Calculation is a reformatted function found at [css-tricks.com](http://css-tricks.com/snippets/php/time-ago-function/)
License used is [WTFPL](http://www.wtfpl.net/)