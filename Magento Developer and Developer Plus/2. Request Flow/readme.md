# Request Flow


### Application initialization

  - [ ] Describe the steps for application initialization
  - [ ] Describe the role of the system entrypoint, index.php

    

### Front Controller

  - [ ] Describe the role of the front controller
  - [ ] Identify uses for events fired in the front controller

    

### URL rewrites

  - [ ] Describe URL structure/processing in Magento
  - [ ] Describe the URL rewrite process

    

### Request routing

  - [ ] Describe request routing/request flow in Magento
  - [ ] Describe how Magento determines which controller to use and how to customize
route-to-controller resolution

    

### Module initialization

  - [ ] Describe the steps needed to create and register a new module
  - [ ] Describe the effect of module dependencies
  - [ ] Describe different types of configuration files and the priorities of their loading  

    

### Design and layout initialization

  - [ ] Identify the steps in the request flow in which:
  	- Design data is populated
  	- Layout configuration files are parsed
  	- Layout is compiled
  	- Output is rendered

    

### Flushing data (output)

  - [ ] Describe how and when Magento renders content to the browser
  - [ ] Describe how and when Magento flushes output variables using the front controller

    

### Code References for this section

	index.php
	Mage_Core_Model_App::run()
	Mage_Core_Model_Config::loadBase() and init()
	Mage_Core_Controller_Varien_Front::init() and dispatch()
	Mage_Core_Controller_Varien_Front::dispatch()
	Mage_Core_Model_Url_Rewrite::rewrite()
    Mage_Core_Controller_Varien_Router_Standard::collectRoutes() and match()
    Mage_Core_Controller_Varien_Action::loadLayout()
    Mage_Core_Model_Layout::__construct()
    Mage_Core_Model_Layout_Update::load()
    Mage_Core_Controller_Response_Http and super classes
    Mage_Page_Block_Html_Head::getCssJsHtml()
    
    
    