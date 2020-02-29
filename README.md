## [TrekDB](http://www.maravento.com)

**TrekDB** replicates or restore data from MySQL or MariaDB databases (and associated files) into the "data" folder, using TREK (to migrate) and RESTORE (to restore) / **TrekDB** replica o restaura datos de las bases de datos MySQL o MariaDB (y archivos asociados) dentro de la carpeta "data", usando las opciones TREK (para migrar) y RESTORE (para restaurar)

### DATA SHEET

|File|Version|OS|Update|Size|
| :---: | :---: | :---: | :---: | :---: |
|[trekdb.exe (.zip)](https://raw.githubusercontent.com/maravento/trekdb/master/trekdb.zip)|1.0|Windows 7/8/10 x86 x64|Feb 19/2020|2.1 MB|

### HOW TO USE
---

Disable your Antivirus, Antimalware, SmartScreen or any other security solution in your Operating System, close all windows and check the date and time of your PC is correct. Unzip trekdb.exe (.zip) to your desktop, execute it with double click (accept privileged execution) and follow the instructions on the screen

Desactive su Antivirus, Antimalware, SmartScreen o cualquier otra solución de seguridad en su Sistema Operativo, cierre todas las ventanas y verifique la fecha y hora de su PC sea la correcta. Descomprima trekdb.exe (.zip) en el escritorio, ejecutarlo con doble clic (acepte la ejecución con privilegios) y siga las instrucciones en pantalla

### IMPORTANT BEFORE USE
---

- These tools are designed for [Wampserver](http://wampserver.aviatechno.net/?lang=en). Compatibility with other environments is not guaranteed / Estas herramientas están diseñadas para [Wampserver](http://wampserver.aviatechno.net/?lang=en). No se garantiza compatibilidad con otros entornos
- The TREK option migrates the contents of the "source" directory (for MARIADB: "\bin\mariadb\mariadb(version)\data" and for MYSQL: \bin\mysql\mysql(version)\data") to the "destination" directory (c:\MySQLTREK or c:\MARIADBTrek) and the RESTORE option restores the contents of the "destination" directory to the "source" directory / La opción TREK migra el contenido del directorio "origen" (Para MARIADB: "\bin\mariadb\mariadb(version)\data" y Para MYSQL: \bin\mysql\mysql(version)\data") al directorio "destino" (c:\MySQLTREK o c:\MARIADBTrek) y la opción RESTORE restaura el contenido del directorio "destino" al directorio "origen"
- These tools use [Robust File Copy](https://en.wikipedia.org/wiki/Robocopy), which has some limitations and may not achieve the desired results. Use them at your own risk / Estas herramientas utilizan [Robust File Copy](https://es.wikipedia.org/wiki/Robocopy), el cual tiene algunas limitaciones y puede no obtener los resultados deseados. Úselas bajo su propio riesgo

##### DB Selector

Select the database to migrate. Press Cancel to exit / Seleccione la base de datos a migrar. Pulse Cancel para salir

[![Image](https://1.bp.blogspot.com/-5iTkm91Ossw/Xk6__9A2jeI/AAAAAAAAE1c/38DmBGgb9LcNRrEN0fY1brNye--HATRyACLcBGAsYHQ/s1600/trekdb-selector.png)](https://www.maravento.com)

##### MySQL

MySQL Trek replicates or restore data from MySQL databases (and associated files) into the "data" folder, using TREK (to migrate) and RESTORE (to restore) / MySQL Trek replica o restaura datos de las bases de datos MySQL (y archivos asociados) dentro de la carpeta "data", usando las opciones TREK (para migrar) y RESTORE (para restaurar)

[![Image](https://1.bp.blogspot.com/-k8JwN332rao/Xk6__VhRMYI/AAAAAAAAE1Y/nvrHI_2bpZUTNETbWgX9MjyFy-YDUexwwCLcBGAsYHQ/s1600/trekdb-mysql.png)](https://www.maravento.com)

If you selected the TREK option at the end, the following message will appear: / Si seleccionó la opción TREK al finalizar saldrá el siguiente mensaje:

[![Image](https://1.bp.blogspot.com/-QOUtCRdfs0E/Xk6_-wCDioI/AAAAAAAAE1U/gHbzXrkB1L4KtkioDWdrZkArUkp4LkzUgCLcBGAsYHQ/s1600/trekdb-mysql-trek.png)](https://www.maravento.com)

If you selected the RESTORE option at the end, the following message will appear: / Si seleccionó la opción RESTORE al finalizar saldrá el siguiente mensaje:

[![Image](https://1.bp.blogspot.com/-VG4socUO104/Xk6_-jGy70I/AAAAAAAAE1Q/Yfg9F9n9XrgwUYLDtKB_hfbI-ZGqYRfvQCLcBGAsYHQ/s1600/trekdb-mysql-restore.png)](https://www.maravento.com)

##### MariaDB

MariaDB Trek replicates or restore data from MariaDB databases (and associated files) into the "data" folder, using TREK (to migrate) and RRESTORE (to restore) / MariaDB Trek replica o restaura datos de las bases de datos MariaDB (y archivos asociados) dentro de la carpeta "data", usando las opciones TREK (para migrar) y RESTORE (para restaurar)

[![Image](https://1.bp.blogspot.com/-8mqhVZ5Bjf0/Xk6_-ERVNkI/AAAAAAAAE1M/EgSQ3EJcsR03mBIZYcZTAcRnG8ZyMcXCQCLcBGAsYHQ/s1600/trekdb-mariadb.png)](https://www.maravento.com)

If you selected the TREK option at the end, the following message will appear: / Si seleccionó la opción TREK al finalizar saldrá el siguiente mensaje:

[![Image](https://1.bp.blogspot.com/-ul8z2k6NTGA/Xk6_-MUyfiI/AAAAAAAAE1I/ql7eVCRBNvo4KHgYSqESzcbIM7G0rsNPQCLcBGAsYHQ/s1600/trekdb-mariadb-trek.png)](https://www.maravento.com)

If you selected the RESTORE option at the end, the following message will appear: / Si seleccionó la opción RESTORE al finalizar saldrá el siguiente mensaje:

[![Image](https://1.bp.blogspot.com/-lV62G33W8FQ/Xk6_-IDNZLI/AAAAAAAAE1E/tQsAExhZKuM5lv46VwIK--sIEWWDnyaBwCLcBGAsYHQ/s1600/trekdb-mariadb-restore.png)](https://www.maravento.com)

### CONTRIBUTIONS
---

We thank all those who contributed to this project / Agradecemos a todos los que han contribuido con este proyecto

### DONATE
---

BTC: 3M84UKpz8AwwPADiYGQjT9spPKCvbqm4Bc

### LICENCES
---

[![GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl.txt)

[![CreativeCommons](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)
[maravento.com](http://www.maravento.com) is licensed under a [Creative Commons Reconocimiento-CompartirIgual 4.0 Internacional License](http://creativecommons.org/licenses/by-sa/4.0/).

[WinZenity](https://github.com/maravento/winzenity), [Jpsoft](https://jpsoft.com/), [SteelWerX](https://fstaal01.home.xs4all.nl/swreg-us.html), [Microsoft](https://www.microsoft.com/), [74cz](http://74.cz/es/make-sfx/index.php), [Resource Hacker](http://www.angusj.com/resourcehacker/), [7zSFX Builder](https://sourceforge.net/projects/s-zipsfxbuilder/)

© 2020 [Maravento Studio](http://www.maravento.com)

### DISCLAIMER
---

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
