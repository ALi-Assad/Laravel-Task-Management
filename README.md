
# Task management

A small system for task management with a sort feature using drag and drop.

## Features

- Create project
- Select a project from the dropdown
- Create tasks for the selected project
- Delete and update task
- Resort tasks using drag and drop


## Appendix

- Framework: Laravel
- Tools: Ajax
- Libraries: jQuery (jQuery UI)
- Icon toolkit: Font Awesome 


## How it works

We are always dealing with one task because we should have one and only one task with 1 priority and the other with 2, so we have one process and two scenarios.

#### The process:
When changing any task's priority to 1 check if we have a task with 1 priority and change it to 2. 

#### The first scenario: 
   Create or update any task's priority to 1 the system 
  will change this task's priority to  2 and check if there is a task with 1 
  priority and change it to 2.

#### The second scenario: 
  Drag and drop any task to the top of the list (and only at the top) the 
   system will change this task's priority to 1 and check if there is a 
   task with 1 priority and change it to 2.

   
   ##### Create project:
   When creating a new project, the new project will be created, and the system will redirect you to the show project page and automatically select the new project in the dropdown
## Deployment

To deploy this project run
```bash
   composer install
```

Then migrate the DB
```bash
  php artisan migrate:fresh
```

Copy and best this link in your browser to start your journey
```bash
 your-domain/task-management/public/project/index
```

