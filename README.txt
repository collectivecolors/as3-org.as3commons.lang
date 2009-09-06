as3-commons language component releases for use as Git submodules in 
ActionScript or Flex applications.

****************************
* IMPORTING AS A SUBMODULE *
****************************

The following instructions assume that you have a git repository set up on your
application directory.

To import this package into your application, run :

----------
 Commands 
 
$  git submodule add git@github.com:collectivecolors/as3-org.as3commons.lang.git
                     {SOURCE_DIR}/org/as3commons/lang
                     
$  git submodule init

----------

Where :

 {SOURCE_DIR} is your root source folder.  
    
    If your repository is at the root source path then just use the package
    name, org/as3commons/lang 

*********
* NOTES * 
*********

1. We did not create and are not the maintainers of the as3commons language 
   components.  Thanks to Christophe Herreman and team at 
   http://code.google.com/p/as3-commons/people/list! 
   
2. Please see http://code.google.com/p/as3-commons/ for more information about 
   as3commons language components.

3. The official svn repository from which this git repo is based upon is 
   http://as3-commons.googlecode.com/svn.
   
4. We will try to update this repository as close to actual svn release as 
   possible.  If you notice that this repo is stale then send us a message 
   and we'll update it.