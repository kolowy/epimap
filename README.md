# Epimap
Project available on https://epimap.fr

Web application for Epita campus maps.
Epimap is not affiliated with EPITA or IONIS Education Group, 
which means that neither of these organizations and its affiliates have authority over this project.
For more information on authorizations, please refer to the license.

Maps are based on a previous work of Ivan Colona (map.epita.eu) https://github.com/gconfs/epimap

[<img alt="Deployed with FTP Deploy Action" src="https://img.shields.io/badge/Deployed With-FTP DEPLOY ACTION-%3CCOLOR%3E?style=for-the-badge&color=2b9348">](https://github.com/SamKirkland/FTP-Deploy-Action)

## Contributing

### Epimap 

1. Go to your local epimap directory (after cloning it)
2. Start a local http server (python 3 needed)
```sh
$ python3 -m http.server
```
3. Checkout [http://0.0.0.0:8000]().

### SVG Maps

Here is the process to update maps properly:

1. Open SVG in Inkscape (or AdoBe Illustrator) 
2. Update the map (tutorial: )
3. Save file, close your editing software and open the file in your favorite text editor
4. Check for width and height properties in svg header: values should be "100%"

This last point is mandatory to pass CD workflow action and then be merged and deployed

## Last Updates:

### May, 2022
- Workflow added (CD // GH actions: tests and checks, autodeploy)

### April, 2022
- Pasteur maps major updated
- Dark mode and key map added

### December 2021
- Paritalie maps added (Missing names)
- Last Update added in Right Bottom Navbar
- Clean Up in KB maps