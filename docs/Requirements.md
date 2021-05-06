# Todo-API-Requirements

## Why

To do API provides a simple way for people to manage their tasks.

## User stories 

- As a user I want to create a task with a name, description and wheter it has been completed.
- As a user I want the created task to display on my table.
- As a user I want to update the task and its values.
- As a user once the task is completed I want to mark it as completed.
- As a user I want to delete the tasks that belong to me if any mistakes have been made.

## Data Model
```json
{
  "id": 0,
  "name": "string",
  "completed": true,
  "completed_at": "datetime",
  "created_at": "datetime",
  "updated_at": "datetime"
}
``` 