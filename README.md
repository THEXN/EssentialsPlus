# EssentialsPlus
## for TShock5 by Average#1305
## 汉化：肝帝熙恩
Essentials+ 是 Essentials 和 MoreAdminCommands 的优化组合。所有命令都是异步运行的。
不包括标志命令。

## 命令 ##

- /find -> 包含多个子命令:
    -command -> 根据输入搜索特定命令，返回匹配的命令及其权限。
    -item -> 根据输入搜索特定物品，返回匹配的物品及其ID。
    -tile -> 根据输入搜索特定方块，返回匹配的方块及其ID。
    -wall -> 根据输入搜索特定墙壁，返回匹配的墙壁及其ID。
- /freezetime -> 冻结/解冻时间。
- /delhome <家名称> -> 删除指定名称的家。
- /sethome <家名称> -> 设置一个名为<家名称>的家。
- /myhome <家名称> -> 传送到您的名为<家名称>的家。
- /kickall <标志> <原因> -> 踢出每个玩家，原因为<原因>。有效标志: -nosave -> 踢出不保存SSC背包。
- /= -> 重复您最后输入的命令（不包括 /= 的其他迭代）。
- /more -> 最大化手持物品的堆叠。子命令:
    -all -> 最大化玩家背包中所有可堆叠的物品。
- /mute -> 覆盖TShock的 /mute 命令。包含子命令:
    - add <名称> <时间> -> 为名称为<名称>的用户添加静音，时间为<时间>
    - delete <名称> -> 删除名称为<名称>的用户的静音
    - help -> 输出命令信息
- /getpvp2 -> 开启/关闭PvP状态
- /ruler [1|2] -> 测量1和2之间的距离。
- /sudo [标志] <玩家> <命令> -> 尝试让<玩家>执行<命令>。有效标志: -force -> 强制运行命令，不受<玩家>权限限制。拥有 essentials.sudo.super 权限的玩家可以在任何人身上使用 /sudo。
- /timecmd [标志] <时间> <命令> -> 在<时间>后执行<命令>。有效标志: -repeat -> 每隔<时间>重复执行<命令>
- /back [步数] -> 将您带回之前的位置。如果指定了 [步数]，则尝试将您带回[步数]步之前的位置。
- /down [层数] -> 尝试向地图下移动。如果指定了 [层数]，则尝试向下移动 [层数] 次。
- /left [层数] -> 与 /down [层数] 相同，但向左移动。
- /right [层数] -> 与 /down [层数] 相同，但向右移动。
- /up [层数] -> 与 /down [层数] 相同，但向上移动。

## 权限 ##

- essentials.find -> 允许使用 /find 命令。
- essentials.freezetime -> 允许使用 /freezetime 命令。
- essentials.home.delete -> 允许使用 /delhome 和 /sethome 命令。
- essentials.home.tp -> 允许使用 /myhome 命令。
- essentials.kickall -> 允许使用 /kickall 命令。
- essentials.lastcommand -> 允许使用 /= 命令。
- essentials.more -> 允许使用 /more 命令。
- essentials.mute -> 允许使用改进的 /mute 命令。
- essentials.pvp -> 允许使用 /pvp 命令。
- essentials.ruler -> 允许使用 /ruler 命令。
- essentials.send -> 允许使用 /send 命令。
- essentials.sudo -> 允许使用 /sudo 命令。
- essentials.sudo.force -> 扩展 sudo 的功能。
- essentials.sudo.super -> 允许在任何人身上使用 sudo。
- essentials.sudo.invisible -> 导致 sudo 命令执行时不可见。
- essentials.timecmd -> 允许使用 /timecmd 命令。
- essentials.tp.back -> 允许使用 /back 命令。
- essentials.tp.down -> 允许使用 /down 命令。
- essentials.tp.left -> 允许使用 /left 命令。
- essentials.tp.right -> 允许使用 /right 命令。
- essentials.tp.up -> 允许使用 /up 命令。
