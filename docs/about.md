## About the Project

This is a test repo for setting up MKDocs for Data Engineering

``` mermaid
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
    A ----> C;
    B ----> C;
    linkStyle 0 color:green;
    linkStyle 1 color:green;
```

## Serve MkDocs on another port:
* mkdocs serve -a localhost:9999
* mkdocs serve --dev-addr=0.0.0.0:8081