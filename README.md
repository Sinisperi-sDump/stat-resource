# stat-resource

> Stat for your Godot needs

Stat is a resource mainly for tracking health and similar stats.

## value

Current value of the stat.  
From `0` to `max_total()` (`max_value + max_bonus`)

## temp_value

Extra value on top of normal value.  
Can go over `max_total()`.  
From `0` to `inf`

## max_value

Maxium for the value that it can't go over.  
From `0` to `inf`

## max_bonus

Extra max value on top of normal max value.  
From `0` to `inf`

## value_total()

returns `value + temp_value`

## max_total()

returns `max_value + max_bonus`
