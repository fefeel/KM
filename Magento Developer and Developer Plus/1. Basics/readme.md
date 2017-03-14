# Basics


### High-level Magento architecture

  - [x] Describe Magento codepools
  - [x] Describe typical Magento module structure
  - [x] Describe Magento templates and layout files location
  - [x] Describe Magento skin and JavaScript files location
  - [x] Identify and explain the main Magento design areas (adminhtml and frontend)
  - [x] Explain class naming conventions and their relationship with the autoloader
  - [x] Describe methods for resolving module conflicts.

    

### Magento configuration

  - [x] Explain how Magento loads and manipulates configuration information
  - [x] Describe class group configuration and use in factory methods
  - [x] Describe the process and configuration of class overrides in Magento
  - [x] Register an Observer
  - [x] Identify the function and proper use of automatically available events, including
*_load_after, etc.
  - [x] Set up a cron job

    

### Internationalization

  - [x] Describe how to plan for internationalization of a Magento site
  - [x] Describe the use of Magento translate classes and translate files
  - [x] Describe the advantages and disadvantages of using subdomains and subdirectories in internationalization

    

### Code References for this section

	Mage_Core_Model_App
	Mage_Core_Model_Config
	Mage_Core_Model_Resource_Db_Collection_Abstract
	Varien_Autoload
	Mage_Core_Model_App_Area
	Mage_Core_Model_Store
    Varien_Event_Observer
    Mage_Core_Model_Translate::init()
    Mage_Core_Model_Locale::emulate()
    