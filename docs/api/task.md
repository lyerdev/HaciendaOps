---
layout: page
---

# `tasks` resource

Base endpoint:

```shell

{server_url}/task
```

Provides information about pending and ongoing tasks at the farm using HaciendaOps API.

## Resource properties

Sample `task` resource

```js

{
    "id": 1,
    "title": "Morning irrigation",
    "description": "Water the plants in Garden A",
    "task_type": "Watering",
    "due_date": "2024-06-05",
    "completed": false,
    "kaizen_notes": "Consider changing to sunrise-only watering and reduce evaporation."
}
```

| Property name | Type | Description |
| ------------- | ----------- | ----------- |
| `id` | number | The task's unique record ID |
| `title` | string | The title of the task |
| `description` | string | A short description of the task |
| `task_type` | string | The task's category |
| `due_date` | string | The [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) format of the date and time the task is due |
| `completed` | string | The status of the task |
| `kaizen_notes` | string | Details about task improvements |

## Read

* Get task

## Create

* Add a task

## Update

* Patch a task
