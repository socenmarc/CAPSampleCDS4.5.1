# Steps

Site de CAP https://cap.cloud.sap/docs/ <--> aquí hi és tot, està molt bé aquesta ajuda. Hi ha una secció Getting Started / in a Nutshell molt potent.

Preparació de l'entorn -> https://cap.cloud.sap/docs/get-started/#local-setup

El que he fet jo de manera ràpida és:
- cds init nom_del_projecte --add samples
- cd nom_del_projecte
- code .
Desde terminal de vscode (tot i que també ho pots fer desde linia de comandes):
- cds watch     <--> això et desplega l'app en local per http://localhot:4004
Per afegir una app necessites més coses, si vols saber-ho et passo el que necessites.

# Getting Started

Welcome to your new project.

It contains these folders and files, following our recommended project layout:

File or Folder | Purpose
---------|----------
`app/` | content for UI frontends goes here
`db/` | your domain models and data go here
`srv/` | your service models and code go here
`package.json` | project metadata and configuration
`readme.md` | this getting started guide


## Next Steps

- Open a new terminal and run `cds watch` 
- (in VS Code simply choose _**Terminal** > Run Task > cds watch_)
- Start adding content, for example, a [db/schema.cds](db/schema.cds).


## Learn More

Learn more at https://cap.cloud.sap/docs/get-started/.
