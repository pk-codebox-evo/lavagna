# Roadmap

This is a high level roadmap. Lavagna has currently:

 - a stable 1.0.x branch where small fixes and features will be added. Some of the work done in the master branch will be backported.
 - the current master (1.1) where the big features are developed

## Expected for 1.0.3 (~september 2015)

 - iCalendar feed support [merged, still WIP]
 - update to spring 4.2.x  [done]
 - switch connection pool to hikaricp (simplify configuration)  [done]
 - use the browser locale for showing the correct first day of the week in the calendar (sunday or monday)  [done]

## Expected for 1.1 

 - client side refactoring, porting to angular 1.4.x
 - decent i18n
 - improve the UI/UX
 - enable Content-Security-Policy
 - refactor the authentication manager: cleanup + simplification
 - support gitlab oauth 
 - support internal account handling
 - support commit log parsing (git, svn (?))
 - webhooks support
 - update to spring 4.2.x [done]
 - switch connection pool to hikaricp [done]

  