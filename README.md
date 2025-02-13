The purpose of this repository is to describe the relationships between various entities in the cloud-native geospatial, including:
- software tools, libraries, and services
- data formats
- organizations
 
Obsidian is used to define relationships (with internal links, tags, and properties) and to visualize the relationships through interactive graphs. 

![](obsidian-cng-screencast.gif)





```mermaid
flowchart TD

B(Obsidian<br/>Vault) <--> |sync| A(GitHub<br/>repository)

C(content<br/>change) --> |Pull Request| A
```



