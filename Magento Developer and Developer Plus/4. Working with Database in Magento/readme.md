# Working with Database in Magento


### Models, resource models, and collections

  - [ ] Describe the basic concepts of models, resource models, and collections, and the relationship they have to one another
  - [ ] Configure a database connection
  - [ ] Describe how Magento works with database tables
  - [ ] Describe the load-and-save process for a regular entity
  - [ ] Describe group save operations
  - [ ] Describe the role of Zend_Db_Select in Magento
  - [ ] Describe the collection interface (filtering/sorting/grouping)
  - [ ] Describe the hierarchy of database-related classes in Magento
  - [ ] Describe the role and hierarchy of setup objects in Magento

    

### Install/upgrade scripts

  - [ ] Describe the install/upgrade workflow
  - [ ] Write install and upgrade scripts using set-up resources
  - [ ] Identify how to use the DDL class in setup scripts

    

### Code References for this section

	Mage_Core_Model_Abstract
	Mage_Core_Model_Resource_Db_Abstract
	Mage_Core_Model_Resource_Db_Collection_Abstract
	Mage_Core_Model_Resource::getTableName()
	Zend_Db_Select
	Mage_Core_Model_App::run() and _initModules()
    Mage_Core_Model_Resource_Setup::applyAllUpdates() and applyAllDataUpdates()
    Mage_Eav_Model_Entity_Setup::addAttribute() and updateAttribute() 
    