# Compucorp Junior Devops/Sysadmin Task: 

Drupal and CiviCRM secure cloud installation <b>with SSL certificate using https://letsencrypt.org/</b>


Creation of a new server with Drupal 7 and CiviCRM .

<ul>
  <li>The server should use Nginx on an AWS micro instance. You can create an AWS free trial account for the purpose of this exercise.</li>


<li>You should install Drupal 7 and CiviCRM on this server in a secure fashion with SSL certificate from https://letsencrypt.org/.<br> 
You may wish to research what Nginx configurations are required to make both Drupal AND CiviCRM secure.</li> 
<li>Please install CiviCRM and Drupal in different databases as this is considered best practice.</li> 
<li>Configure Drupal to have a private files folder. Ensure this is secure within your NGINX configuration.</li> 
<li>Ensure that the Nginx configuration is secure for Drupal and CiviCRM including any other files upload folders.</li> 
<li>Modify the CiviCRM settings file so that the CiviCRM extension directory is set using settings files variables (https://docs.civicrm.org/sysadmin/en/latest/customize/settings/)</li> 
<li>Make sure you install all necessary packages required for a server to run Drupal 7/civicrm .i.e mysql,php,nginx.</li> 
<li>We prefer Ubuntu 16.04.</li> 
<li>Install Drush to the server for the appropriate user</li> 
<li>Modify the Drupal settings files so that Drupal views can use the CiviCRM database (https://wiki.civicrm.org/confluence/display/CRMDOC/Views3+Integration)</li> 
<li>We require that the site is backed up daily/weekly/monthly. Choose an appropriate method for this, explain your reasoning. You can use any method as long as backups are made as described.</li> 
</ul>
<p>
<b>Please then send us the following:</b>
<p>
<li> Send us links to the site and all server and site root passwords so we can review the configuration.</li> 
<li> Send us appropriate documentation of all the steps you took in the form of a “How to Guide”</li> 
<li> Send us links to any references for configuration files and/or standards that you have used</li> 
<p>
<b>(Please note: Use LetsEncrypt for ssl certificates with automated renewal).</b>
<p>
We recommend to use AWS free tier for hosting.

