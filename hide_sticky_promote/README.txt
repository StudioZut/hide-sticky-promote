Hide Sticky and Promote
=======================

Installing
----------
Move the module folder to your site's module directory (usually 
/sites/all/modules). Look for it on the modules list at /admin/modules. 
Check the box and save to enable. 

By default the module will remove the 'sticky' and 'promote' options 
from content admin pages. You can set permissions for the module to 
override the default, which reverts to the normal options when creating 
or editing content. This can be done from /admin/people/permissions or 
from the 'permissions' link next to the module name in the modules list.

Note that the module does not alter your sites functionality when it 
comes to 'sticky' and 'promoted' content: it only removes the option 
to make content sticky/unsticky or promoted/demoted.
 

Developer
---------
Christian Aldridge http://github.com/studiozut

From .info description: This module removes the "promote to front page" 
and "sticky" checkboxes when creating and editing content. Permissions 
can be set for user roles to restore the checkboxes and use the "sticky" 
and "promote" options when creating or editing content.

*(thanks to Roger Codina's fork at Roger Codina 
http://github.com/rogercodina/hide-sticky-promote 
and Elijah Lynn's post at 
http://drupal.stackexchange.com/questions/4612/
how-to-disable-promote-to-front-page-and-sticky-options)*
