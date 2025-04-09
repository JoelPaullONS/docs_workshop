# Title: Project Name

----------------------------------------------------------------------------------------------------------------

                                                  Introduction to the Project. 

---------------------------------------------------------------------------------------------------------------- 

Flow Diagram to visually show how data enters the pipeline, is processed and exits the pipeline, e.g. show data journey
```
mermaid2
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#BB2528',
      'primaryTextColor': '#fff',
      'primaryBorderColor': '#7C0000',
      'lineColor': '#F8B229',
      'secondaryColor': '#006100',
      'tertiaryColor': '#fff'
    }
  }
}%%
flowchart
    A[My Docs 1]
    B[My Docs 2]
    C[My Docs 3]
    A --> C
    B --> C
    linkStyle 0 color:green
    linkStyle 1 color:green
```

## Serve MkDocs using VS Code:
* mkdocs serve -a localhost:9999
* mkdocs serve --dev-addr=0.0.0.0:8081

## How to use GitHub pages?...