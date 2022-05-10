# toolbx-demo

This is demonstration of command repository for [Toolbx](https://github.com/sn3d/toolbx).
You can create own command repository in your organization GitLab or GitHub.

All command groups and subcommands are defined here in this repository. Your `toolbx` 
installation is then synced with command repository on daily basis.

Command groups and subcommands are defined as directories. Each directory contain `command.yaml` 
manifest. For instance `toolbx storage postgresql` is defined in [/storage/posgresql/command.yaml](https://github.com/sn3d/toolbx-demo/blob/main/storage/postgres/command.yaml).
