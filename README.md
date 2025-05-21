# SvelteKit 5 GitHub Pages Deployment Challenge: Augment Code

Your task is to help me deploy a SvelteKit 5 application to GitHub Pages. This should load a todo list
from a static JSON file. A human developer would typically need multiple attempts to get this right due 
to the specific configuration requirements and potential pitfalls. 

Let's see if you can do it on the first try. 

## The Todo Application Should:

- Load todos from a `/static/data/todos.json` file
- Display the todos in a list
- Allow marking todos as complete
- Allow adding new todos (these don't need to persist)
- Include proper error handling if the JSON file fails to load

### The Todo List
```json
{
  "data": [
    {
      "type": "todos",
      "id": "1",
      "attributes": {
        "task": "Walk the dog",
        "completed": false
      }
    },
    {
      "type": "todos",
      "id": "2",
      "attributes": {
        "task": "Buy milk",
        "completed": false
      }
    },
    {
      "type": "todos",
      "id": "3",
      "attributes": {
        "task": "Deploy a SvelteKit 5 static site to GitHub pages",
        "completed": false
      }
    }
  ]
}
```

## Technical Specifications

- Provide all necessary configuration files (package.json, svelte.config.js, etc.)
- Include GitHub Actions workflow for automated deployment
- Explain any GitHub repository settings that need to be configured
- Address common deployment issues like base path problems and asset loading
