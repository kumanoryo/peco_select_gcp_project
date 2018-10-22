# peco_select_gcp_project
fish shell plugin: GCP project selecter.

## Requiments
- [fish shell](https://fishshell.com/) >= 2.7.1
- [Google CLOUD SDK](https://cloud.google.com/sdk/) >= 221.0.0
    - Add [config configurations](https://cloud.google.com/sdk/gcloud/reference/config/configurations/)
- [peco](https://github.com/peco/peco) >= 0.5.1

## Installation
With [fisher](https://github.com/jorgebucaran/fisher)
```console
fisher install kumanoryo/peco_select_gcp_project
```

## Usage
```console
peco_select_gcp_project
peco_select_gcp_project <your_gcp_project_name>
# alias
gpj
gpj <your_gcp_project_name>
# keybind
Ctrl + g -> p
```

## Alias
Default alias name: `gpj`. 
Update this file, if you want to change alias name,
`<your_fish_shell_pass>/conf.d/peco_select_gcp_project_key_bindings.fish`
```fish
alias gpj "peco_select_gcp_project"
↓
alias <your_alias> "peco_select_gcp_project"
```

## Keybind(option)
Default keybind: Ctrl + g -> p.
Update this file, if you want to change keybind.
`<your_fish_shell_pass>/functions/fish_user_key_bindings.fish`
```fish
bind \cgp peco_select_gcp_project
↓
bind <your_keybind> peco_select_gcp_project
```

## License
peco_select_gcp_project is MIT Licensed.