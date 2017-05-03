# geosciml.org
This repository contains all of the static website code for the [www.geosciml.org]([http://www.geosciml.org) website. It also includes:

* [resource.geosciml.org](http://resource.geosciml.org)
* [schemas.geosciml.org](http://schemas.geosciml.org)

### Copyright & License
This site's code and this repository are copyright the [IUGS Commission for the Management and Application of Geoscience Information (CGI)](http://www.cgi-iugs.org/)

This site's code and all the textual content are licensed for reuse under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license. See [LICENSE](LICENSE) for a copy of the deed.

### Tools used

This site contains: 

* static HTML generated by tools such as Enterprise Architect
* XSD schemas generated by FullMoon and ShapeChange
* XML documents generated in XML editors like Oxygen, and Microsoft Xecel
* RDF files generated in tools such as Protege, TopBraid, Oxygen, and XSLT translators
* The 5 or so main pages of this website are pages rendered into HTML by PHP which interprets Markdown text files using the Parsedown PHP plugin. 

### Project Structure
The following directories in this repository manage the following content:

* **pages**: all of the Markdown files used to make site HTML pages
* **reference_database**: the single reference_database zip file
* **resource**: resource.geosciml.org website
* **schemas**: schemas.geosciml.org website
* **theme**: theming files for all the websites stored here
* **vendor**: PHP packages this website depends on (only parsedown for now)

The files in this main directory do the following things:

* **.gitignore**: a file used by the Git version control system to exclude certain files
* **composer.json**: basic project description file for the PHP package manager system Composer
* **composer.lock**: the detailed Composer package manager's specifications file for this project
* **index.php**: the main or initial web page for this site. Reads pages/geosciml.org.md
* **LICENSE**: the license for this repository code and content. Creative Commons BY 4.0
* **news_archive.php**: the News Archive section of the website. Reads pages/news_archive.md
* **README.md**: this file. The documentation entry point for this repository 
* **settings.php**: global settings used by multiple PHP files
* **TODO.txt**: a list of todo items provided to assist future developers of this repository 

### Authors
The authors of this content are:

* **CGI members**
    * **Ollie Raymond** (from GA)
    * **other CGI members** including Simon Cox from CSIRO

Technical author of this code as a repository is:

**Nicholas Car**  
Data Architect  
<nicholas.car@ga.gov.au>  
http://orcid.org/0000-0002-8742-7730  
