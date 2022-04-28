<link href="{{ 'bootstrap.css' }}" rel="stylesheet">

## Welcome to GitHub Pages
#Testing:
This is where I am going to be documenting my screeps library soon :)

```JS
export var rampartWorkerCreep = { // W,C,M
  creep: "none",
  body: [WORK, CARRY, MOVE],
  ratio: [0.25, 0.25, 0.50],
  squad: "none",
  status: QUEUED,
  act: extensionRushFillRole
}
```

| Properties | Description                                         |
|------------|-----------------------------------------------------|
| Creep      | Creep assigned through squad Queue                  |
| Body       | Possible body parts to assign                       |
| Ratio      | Ratio of body parts to spawn. (must == body.length) |
| Squad      | Current Assigned Squad                              |
| Status     | Global defined status (QUEUED, ALIVE, DEAD)         |
| Act        | The function this squad performs each tick          |
