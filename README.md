# sftp-sync
write config file like this. This plugin is use for myself to user now,with a lot of bug may be,you can fix it yourself.I will edit it later. Or see this https://github.com/eshion/vim-sftp-sync
"user config                                                                                              
let s:host1=''
let s:host2=''
let g:host1=''
let g:host2=''
let g:vim_sftp_configs = { 
\      'sample_server_1' : { 
\       'upload_on_save'   : 1,
\       'download_on_open' : 0,
\       'confirm_downloads': 1,
\       'confirm_uploads'  : 0,
\       'local_base_path'  : '',
\       'remote_base_path' : '',
\       'sftp_command' : 'sftp',
\       'complete_prompt_regexp' : '100\%',
\       'user' : 'user',
\       'pass' : 'password',
\       'host' : '-PPORT username@'
\   },  
\      'sample_server_2' : { 
\       'upload_on_save'   : 1,
\       'download_on_open' : 0,
\       'confirm_downloads': 1,
\       'confirm_uploads'  : 0,
\       'local_base_path'  : '',
\       'remote_base_path' : '',
\       'sftp_command' : 'sftp',
\       'complete_prompt_regexp' : '100\%',
\       'user' : 'user',
\       'pass' : 'password',
\       'host' : '-PPORT username@'
\   }
\}
