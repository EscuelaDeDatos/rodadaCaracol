# Sistema de levantamiento de datos El Caracol
### Version
1.0.0
### Installation
Modificar en index.php
  - $servername = "localhost";
  - $username = "userdb";
  - $password = "passdb";
  - $dbname = "namedb";

### Installation
estructura de tabla SQL:
```sh
CREATE TABLE IF NOT EXISTS `reportes` (
  `id` int(254) NOT NULL AUTO_INCREMENT,
  `latlng` varchar(200) NOT NULL,
  `personas` int(9) NOT NULL,
  `img` varchar(250) NOT NULL,
  `fecha` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
  PRIMARY KEY (`id`)
) ENGINE=MyISAM  DEFAULT CHARSET=latin1 AUTO_INCREMENT=3 ;
```
**Free Software, Hell Yeah!**