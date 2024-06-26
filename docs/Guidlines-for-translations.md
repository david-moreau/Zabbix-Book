# Guidelines For Translations

## How to tranlate

- Index pages are in the docs folder the english version is ```index.md``` if we like to tranlate to another language we need to name the page ```index.<language code>.md```. For example index.fr.md, the correct codes are in mkdocs.md 
  The book images have to be created in a folder in mkdocs with the language code Ex: nl, fr
- Translation of the menu can be done in mkdocs.yml. Create the option nav_translations: and translate the menu structure.
  Example:
```
- locale: nl
  name: Nederlands
  build: true
  nav_translations:
    Welcome: Welkom
    Getting started: Aan de slag
    The basics: De basis
    Problem detection: Probleem detectie
```
- If you like to translate a page then create a file with the same name as the original but add the country code before .md Ex : Requirements.md will become Requirements.nl.md. If you don't make screenshots with translations then use the same images in the image dir.
- If you like to add new screenshots create a new folder image.<language code> Ex: image/ becomes image.nl/

## How to write a topic

- All is written in markdown , HTML is supported but try to avoid if not needed
- Start the page with the Header #
- When you write a topic start with an introduction what the topic is about
- Give an overview of the topics that you will cover
- Add visuals if possible this explains better to people how things work
- Create a how to so that people see how they can do this 
- place the images in a /image folder 
    - You can use the english screenshots in the image folder or create your own screenshots in local language use /image.<lang code> ex: /image.fr
- Close every topic with --- this will draw a horizontal line 


## Translation Table 

- This table can be used to track what has been finished and is ready for translation. For this we mark the page with :white_check_mark:. 
- Once other languages are translated we mark them with :checkered_flag:
- In case a page gets updated with new information after pages are already translated we mark the page with :material-refresh: and remove the :checkered_flag: from the tranlated pages.

---

- Webpage is ready for translation: :white_check_mark:
- Webpage is translated : :checkered_flag:
- Webpage has been updated after translation: :material-refresh:
- Webpage is still not finished : :construction:


???+ Note
    Please don't update this table this is for reference only when doing translations. I will maintain this table when I add new topics or merge changes.


| Webpage			| English          | French           | German           | Italian | Dutch | Portugese | Spanish | Thai | Chinese |
|:----				| ----	           | ----             | ----             | ----    | ----  | ----      | ----    |----  | ----    |
|Welcome			|:white_check_mark:|                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|Getting started                |         	   |                  |                  |         |       |           |         |      |         |
|Requirements      		|:white_check_mark:|                  |                  |         |       |           |         |      |         |
|Installing Zabbix DB Server	|:white_check_mark:|                  |                  |         |       |           |         |      |         |
|Installing Zabbix		|:white_check_mark:|                  |                  |         |       |           |         |      |         |
|Configure Zabbix HA		|:white_check_mark:|                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|The basics			|                  |                  |                  |         |       |           |         |      |         |
|Zabbix Interface		|:white_check_mark:|                  |                  |         |       |           |         |      |         |
|Zabbix Users & User groups	|:white_check_mark:|                  |                  |         |       |           |         |      |         |
|Zabbix hosts			|:construction:    |                  |                  |         |       |           |         |      |         |
|Host groups			|:white_check_mark:|                  |                  |         |       |           |         |      |         |
|Interfaces			|:construction:    |                  |                  |         |       |           |         |      |         |
|templates			|                  |                  |                  |         |       |           |         |      |         |
|Items				|                  |                  |                  |         |       |           |         |      |         |
|Zabbix triggers		|                  |                  |                  |         |       |           |         |      |         |
|Macros				|:white_check_mark:|:white_check_mark:|                  |         |       |           |         |      |         |
|Data Flow			|                  |                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|Data collection		|                  |                  |                  |         |       |           |         |      |         |
|Zabbix Agent			|:construction:    |                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|Problem detection		|                  |                  |                  |         |       |           |         |      |         |
|Triggers			|                  |                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|Taking action when problems come|                 |                  |                  |         |       |           |         |      |         |
|Event based Actions		|                  |                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|Managing permissions		|                  |                  |                  |         |       |           |         |      |         |
|Managing Permissions		|                  |                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|Visualising Problems		|                  |                  |                  |         |       |           |         |      |         |
|Visualising our problems	|                  |                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|Automating configuration	|                  |                  |                  |         |       |           |         |      |         |
|Automating configuration	|                  |                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|VMWare monitoring		|                  |                  |                  |         |       |           |         |      |         |
|VMware monitoring with Zabbix	|                  |                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|Monitoring websites		|                  |                  |                  |         |       |           |         |      |         |
|Monitoring websites		|                  |                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|Monitoring SNMP, IPMI and JAVA	|                  |                  |                  |         |       |           |         |      |         |
|SNMP Monitoring		|                  |                  |                  |         |       |           |         |      |         |
|SNMP trap monitoring		|:construction:    |                  |                  |         |       |           |         |      |         |
|JAVA monitoring		|                  |                  |                  |         |       |           |         |      |         |
|IPMI Monitoring		|:construction:    |                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|Authentication			|                  |                  |                  |         |       |           |         |      |         |
|Authentication with HTTP	|                  |                  |                  |         |       |           |         |      |         |
|Authentication with LDAP	|                  |                  |                  |         |       |           |         |      |         |
|Authentication with SAML	|                  |                  |                  |         |       |           |         |      |         |
|Zabbix MFA support		|:white_check_mark:|                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|Monitoring with Proxies	|                  |                  |                  |         |       |           |         |      |         |
|Installing Proxies		|                  |                  |                  |         |       |           |         |      |         |
|Active proxy			|                  |                  |                  |         |       |           |         |      |         |
|Passive proxy			|                  |                  |                  |         |       |           |         |      |         |
|Proxy loadbalancing		|:white_check_mark:|                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|Securing Zabbix		|                  |                  |                  |         |       |           |         |      |         |
|Securing Zabbix Frontend	|:construction:    |                  |                  |         |       |           |         |      |         |
|Securing Zabbix with SELinux	|                  |                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|Maintaining Zabbix		|                  |                  |                  |         |       |           |         |      |         |
|Maintaining Zabbix		|                  |                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|Monitoring Windows		|                  |                  |                  |         |       |           |         |      |         |
|Monitoring Windows		|                  |                  |                  |         |       |           |         |      |         |
|				|                  |                  |                  |         |       |           |         |      |         |
|Zabbix API			|                  |                  |                  |         |       |           |         |      |         |
|Zabbix API			|                  |                  |                  |         |       |           |         |      |         |
|                               |                  |                  |                  |         |       |           |         |      |         |
|Zabbix extras                  |                  |                  |                  |         |       |           |         |      |         |
|Modbus monitoring with Zabbix  |:white_check_mark:|                  |                  |         |       |           |         |      |         |
|                               |                  |                  |                  |         |       |           |         |      |         |
