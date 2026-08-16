# code review submission

## issues found
1. missing type hints infunction signitures
2. poor error handling - used print instead of raising exceptions
3. incorrect import: 'detetimes' instead of 'datetime'

## changes made
added type hints:'str/None' and 'Task/None'to 'create_task'
changed 'print'' to raise value error' instead of 'datetime' 
fixed import to 'from datetime import datetime'

## reflection
this review taught me that type hints make code easier to understand and catch bugs early. Using 'raise' instead of 'print' is better because it stops bad data from being saved.