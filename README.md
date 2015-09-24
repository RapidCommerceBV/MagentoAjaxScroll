# MagentoAjaxScroll
Magento category scroll using AJAX

The magical 10 steps to make this work in your Magento shop?  
1. Clone this repo (DAH!)  
2. Copy it’s contents to the root of your Magento installation. You can use FTP to do that. It’s the directory containing index.php [App] [Skin] [Media] among others  
3. Log in to your Magento backend  
4. Go to System -> Cache Management, select all options, and in the action dropdown select “Refresh”. Then click Submit.  
5. Log out/in to your backend  
6. Go to System -> Configuration -> Catalog and drop down the “Front-end” selection  
7. The extension adds a new option here; “Use jQuery Infinite Ajax Scroll” and this new version adds the option “Use jQuery UItoTop”.  
8. Set both “Use jQuery Infinite Ajax Scroll” and “Use jQuery UItoTop” to “Yes”. Enable the jQuery include option if you do not know what the hell I’m talking about or disable it if it’s already included elsewhere. You can also mess around with the settings that correspond with the new features mentioned above.  
9. Click save config.  
10. All done!  
  
More info: http://www.rapidcommerce.eu/en/blog/category/free-magento-extensions/  
Questions: https://www.facebook.com/RapidCommerce
