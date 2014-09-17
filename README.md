**Orangescrum** is a free, open source, flexible project management web application written using CakePHP.

#### Requirements
    * Apache with `mod_rewrite`
    * PHP 5.3 or higher
    * MySQL 4.1 or higher
  
#### Installation

    * Extract the archive. Upload the content to your server. 
    * Create a new MySQL database (`utf8_unicode_ci` collation) 
    * Get the database.sql file from the root directory and import that to your database.
    * Locate your `app` directory, do the changes on following files:
	  * `app/Config/database.php` - Update the database connection details [Required]
	  * `app/Config/constants.php` - Create a free account in Sendgrid and update the Email sending options [Required]
	  * `app/Config/constants.php` - Change "www.my-orangescrum.com/" to your application domain name [Required]
	  * `app/Config/core-email-settings.php` - Update the Email Contents (OPTIONAL)
    * php.ini settings - change the value of 'post_max_size' and `upload_max_filesize` to 200Mb  (OPTIONAL)
    * Run the application as http://your-site.com/ from your browser and start using Orangescrum
  
#### How to Git

	* Fork the project from GitHub if you are interested in contributing, or you can simply watch its progress.
	* To contribute, clone the repository to your system/working directory
		* Do the require changes to add some features or plug-ins on your local system
		* Do proper testing(including UI) and make sure that the changes are working properly
		* Commit/Push the code to your repository
		* Send a Pull request to Orangescrum git repository



   * **Official website**: [http://www.orangescrum.com](http://www.orangescrum.com)
   * **Blog**: [http://blog.orangescrum.com](http://blog.orangescrum.com)
   * **Downloads**: [http://www.orangescrum.com/downloads](http://www.orangescrum.com/downloads)
   * **Issue Tracker**: [https://github.com/Orangescrum/orangescrum/issues](https://github.com/Orangescrum/orangescrum/issues)
   * **Google Group**: [https://groups.google.com/group/orangescrum-community-support](https://groups.google.com/group/orangescrum-community-support)
   * **Youtube**: [https://www.youtube.com/watch?v=4qCaP0TZuxU](https://www.youtube.com/watch?v=4qCaP0TZuxU)