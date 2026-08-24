2. PLANNING
2.1 identify which files i need to modify 

a) app/models/task.py - Contains the Task model and TaskStatus Enum. i need it verify if ABANDONED is already a valid status. 
b) app/services/task_service.py - Contains the core business logic like check_overdue_tasks() and update_tasks_status().
c) tests/test_task_service.py - to add unit tests for the new rule.

2.2 Outline the changes you would make to implement this rule:
