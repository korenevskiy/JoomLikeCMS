# JoomLikeCMS 
CMS for PHP. Support Templates Joomla and WordPresss. Ability to work without MySQL (with SQLite)

Collected from Joomla but with alteration of certain principles.<br>
1. Support the work without MySQL and MySQL . (support for SQLite).<br>
2. Support Joomla templates and Wordpress.<br>
3. By analogy with the plug Joomla same principle.<br>
4. The templates work as plugins and stored in the folder plugin.<br>
5. Object: An object can be a module and component and article and category.<br>
6. All objects are stored in a single table and can be nested into each other.<br>
7. Objects have different types depending on whether it is a module that category, components, or materials.<br>
8. Each object is created on the basis of installed plug-ins. If the plugin supports the creation of the object.<br>
9. unite concepts of components and modules in object, CMS will output on the page multiple components. Convenient for single-animated websites.<br>
10. Each object is created on the basis of the plug-in, ie component or module can unites with each other tooutput one ID. This allows existing data types to add new fields and links to site for data in list and blogs... and other.<br>
11. In the Templates folder can be copied to a copy of the template modules, components and installed templates. This allows you to change the appearance of the basic design.<br>
12. The data is stored in a single table with different types may search for data by appropriate text or html for all components and modules.<br>
13. In the case of load increase is possible to connect to MySQL, with one touch.<br>
14. Support the entire platform and framework Joomla .<br>
