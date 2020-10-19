{%- if selected_tag == "master" %}
## 这是一个开发版！This is a development version!

这是仅提供给开发人员的测试版！
请不要安装这个版本！

This is **only** intended for test by developers!
Please not install this version!
{% endif %}

{%- if prerelease %}
## 这是一个测试版 This is a beta version

请务必小心不要安装在生产系统上，并且确保你安装前已经做备份

Please be careful and do NOT install this on production systems. Also make sure to take a backup/snapshot before installing. Check the [change log](https://github.com/gyk001/havcs/releases) for more information.
{% endif %}

## HA语音控制技能 Home Assistant Voice Control Skill

支持接入天猫、小度、叮咚等智能音箱

原作者为大大[cnk700i](https://github.com/cnk700i/havcs)，我只是个搬运工，后面可能会基于此做些许~~改进~~破坏，谁知道呢

# Changes
You can find change log under [releases](https://github.com/gyk001/havcs/releases)
