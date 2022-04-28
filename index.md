<link href="{{ 'bootstrap.css' }}" rel="stylesheet">

## Welcome to GitHub Pages

# Testing:

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

backround is not the right color rip
<body>
<link href="{{ 'bootstrap.css' }}" rel="stylesheet">

<h2 id="welcome-to-github-pages">Welcome to GitHub Pages</h2>
<h1 id="testing-">Testing:</h1>
<p>This is where I am going to be documenting my screeps library soon :)</p>
<pre><code class="lang-JS">export var rampartWorkerCreep = { <span class="hljs-comment">// W,C,M</span>
<span class="hljs-symbol">  creep:</span> <span class="hljs-string">"none"</span>,
<span class="hljs-symbol">  body:</span> [WORK, CARRY, MOVE],
<span class="hljs-symbol">  ratio:</span> [<span class="hljs-number">0.25</span>, <span class="hljs-number">0.25</span>, <span class="hljs-number">0.50</span>],
<span class="hljs-symbol">  squad:</span> <span class="hljs-string">"none"</span>,
<span class="hljs-symbol">  status:</span> QUEUED,
<span class="hljs-symbol">  act:</span> extensionRushFillRole
}
</code></pre>
<table>
<thead>
<tr>
<th>Properties</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>Creep</td>
<td>Creep assigned through squad Queue</td>
</tr>
<tr>
<td>Body</td>
<td>Possible body parts to assign</td>
</tr>
<tr>
<td>Ratio</td>
<td>Ratio of body parts to spawn. (must == body.length)</td>
</tr>
<tr>
<td>Squad</td>
<td>Current Assigned Squad</td>
</tr>
<tr>
<td>Status</td>
<td>Global defined status (QUEUED, ALIVE, DEAD)</td>
</tr>
<tr>
<td>Act</td>
<td>The function this squad performs each tick</td>
</tr>
</tbody>
</table>
<p>backround is not the right color rip</p>
</body>
