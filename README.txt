sswifttool
==========

Description:
This tool is designed to be a simple client for Openstack Swift protocol. 
It contains basic functions and some simple automation functions.

Functionality:
get_token 			    Update your token for authorization.
list				    List all avaliable containers.
list_cont			    List objects inside container. Parameters: container_name
get_obj				    View object. Parameters: container_name object_name 
create_cont			    Create container. Parameters: container_name
upload				    Upload file to container. Parameters: container_name object_name full_path_to_file 
delete_obj			    Delete object. Parameters: container_name object_name
delete_cont			    Delete container. Parameters: container_name
delete_cont_list		Delete containers by list. Parameters: path_to_file_with_list
create_cont_list    	Create containers with all objects by list. Parameters: path_to_file_with_list
upload_obj_list			Upload files to some container by list. Parameters: container_name path_to_file_with_list (list format: object_name full_path_to_file)
delete_obj_list 	  	Delete files from some container by list. Parameters: container_name path_to_file_with_list
