## knife commands 

- To upload cookbook
 
`knife cookbook upload <cookbookname>` 

- To run cookbook from workstation 

`knife ssh "tags:patch AND platform:redhat AND chef_environment:97patchingpoc_dev" -x "username" -P "password" "sudo chef-client -o recipe[pas_jenkins_post_patch_linux]"`

 - List of Commands
 
 Chef generate repo
 knife cookbook create cookbookname
 
 if we include other cookbook which has dependencies
 
 we need to add in metadata file `depends cookbooname`
 
 then run berks command `berks install` 
 
 it will download the dependencies to user/.bershelf/cookbooks
 
 Creating a role 
   - add runlist
   
  To see list of roles
   `knife role list`
 
 To add the role
 `kinfe role from_file filename`
 
 `knife role show cookbookname`
 
 `knife cookbook list`
 
 `berks upload --no-ssl-verify`
 
 `knife node list`
 
 `knife node run_list add nodename 'role[cookbookname]'`
 
 
 then run chef-client on the server
