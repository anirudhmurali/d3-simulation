# Tree simulation with D3.js

D3.js is a JavaScript library for manipulating documents based on data. D3 helps you bring data to life using HTML, SVG, and CSS.

## Installation

Follow the above section to install the project.

### Data Manipulation

Provide the tree structure to the ``treeData``. The default structure is:
``  {
    "name": "Root",
    "children": [
      { 
        "name": "Level 2: A",
        "children": [
          { "name": "Level 3: AA" },
          { "name": "Level 3: AB" }
        ]
      },
      { "name": "Level 2: B" }
    ]
  }; ``

You can also use the Hasura's Data APIs to store and retreive the JSON data.

## Additional Resources

* [Official Documentation of D3.js](https://d3js.org/)
* [More D3.js implementations](https://bl.ocks.org/)

## Project structure

### Files and Directories

The project (a.k.a. project directory) has a particular directory structure and it has to be maintained strictly, else `hasura` cli would not work as expected. A representative project is shown below:

```
.
├── hasura.yaml
├── clusters.yaml
├── conf
│   ├── authorized-keys.yaml
│   ├── auth.yaml
│   ├── ci.yaml
│   ├── domains.yaml
│   ├── filestore.yaml
│   ├── gateway.yaml
│   ├── http-directives.conf
│   ├── notify.yaml
│   ├── postgres.yaml
│   ├── routes.yaml
│   └── session-store.yaml
├── migrations/
└── services
    ├── www/
```
# Tree simulation with D3.js

D3.js is a JavaScript library for manipulating documents based on data. D3 helps you bring data to life using HTML, SVG, and CSS.

## Installation

Follow the above section to install the project.

### Data Manipulation

Provide the tree structure to the ``treeData``. The default structure is:
``  {
    "name": "Root",
    "children": [
      { 
        "name": "Level 2: A",
        "children": [
          { "name": "Level 3: AA" },
          { "name": "Level 3: AB" }
        ]
      },
      { "name": "Level 2: B" }
    ]
  }; ``

You can also use the Hasura's Data APIs to store and retreive the JSON data.

## Additional Resources

* [Official Documentation of D3.js](https://d3js.org/)
* [More D3.js implementations](https://bl.ocks.org/)

## Project structure

### Files and Directories

The project (a.k.a. project directory) has a particular directory structure and it has to be maintained strictly, else `hasura` cli would not work as expected. A representative project is shown below:

```
.
├── hasura.yaml
├── clusters.yaml
├── conf
│   ├── authorized-keys.yaml
│   ├── auth.yaml
│   ├── ci.yaml
│   ├── domains.yaml
│   ├── filestore.yaml
│   ├── gateway.yaml
│   ├── http-directives.conf
│   ├── notify.yaml
│   ├── postgres.yaml
│   ├── routes.yaml
│   └── session-store.yaml
├── migrations/
└── services
    ├── www/
```
