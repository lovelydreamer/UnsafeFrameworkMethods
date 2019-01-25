# UnsafeFrameworkMethods

This is a repo to track unsafe methods for different frameworks and JavaScript.


## Native JavaScript:
| Raw HTML                  | Disable Encoding  |     Notes                                  |
| ------------------------- |:-----------------:| ------------------------------------------:|
| innerHTML                 |       TBD         |   - eval()                                 |
|                           |                   |   - calling javascript: protocol directly  |


## Angular:
| Raw HTML                   | Disable Encoding  |    Notes                    |
| -------------------------- |:-----------------:| --------------------:|
| innerHTML                  |       TBD         |     TBD              |
| bypassSecurityTrustHtml    |                   |                      |
|                            |                   |                      |


## React:
| Raw HTML                   | Disable Encoding  |    Notes           |
| -------------------------- |:-----------------:| ------------------:|
| dangerouslySetInnerHTML    |       TBD         |      TBD           |
|                            |                   |                    |



## Django:
| Raw HTML                   | Disable Encoding  |        SQL           |        Notes       |
| -------------------------- |:-----------------:| --------------------:| ------------------:|
|       TBD                  |       safe        |      Manager.raw()   |                    | 
|                            |      is_safe      |      RawSQL          |                    |
|                            |      mark_safe    |      extra()         |                    |


## Soy:
| Raw HTML                   | Disable Encoding  |        SQL           |        Notes       |
| -------------------------- |:-----------------:| --------------------:| ------------------:|
|       TBD                  |  noAutoescape     |                      |                    | 
|                            |                   |                      |                    |
|                            |                   |                      |                    |


## ASPX :
| Raw HTML                   | Disable Encoding  |        SQL           |        Notes       |
| -------------------------- |:-----------------:| --------------------:| ------------------:|
|       TBD                  |  TBD              |                      |                    | 
|                            |                   |                      |                    |
|                            |                   |                      |                    |


