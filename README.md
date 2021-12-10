# Operator's command line interface
This is the [TCN](https://www.tcn.com)'s [Operator](https://operator.tcn.com) command line interface that can be used to create fast and simple integrations.

## Implmented commands

`auth login` - this command will open a browser that will initiate an authentication process and will save a token to disk `$HOME/.opconfig.yaml`  
`org ap list` - list agent groups  
`org pg list` - list permission groups  
`org user list` - list users  
`org user create` - create a user  
`org user enable` - enable user  
`org user disable` - disable user  
`util tz` - list internal timezone ids (to be deprecated)  
`version` - print version  

## Opensource libraries used 
- https://github.com/mitchellh/go-homedir
- https://github.com/skratchdot/open-golang
- https://github.com/spf13/viper
- https://github.com/spf13/cobra
- https://github.com/olekukonko/tablewriter

