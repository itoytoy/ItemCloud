Hi, I will introduce my new plugin : ItemCloud

What is ItemCloud?

ItemCloud is a separated plugin from EconomyPShop, and will be used as library for EconomyPShop in future.
This plugin provides similar functionality to DropBox or Box and etc. It is just for items. You can upload and download unlimited item. It is useful when your inventory is lacking slots.

Usage: /itemcloud upload <item ID[:item damage]>

Aliases
/itmc
/itmc up 276 5
/itmc down 276 5


Features
- Upload and download your items infinitely
- API system
- Data auto save

Commands
/itemcloud register or reg: You MUST use this command before using the service.
/itemcloud upload or up <item ID[:item damage]> <count> : You can upload your item into your account.
/itemcloud download or down <item ID[:item damage]> <count> : You can download your item from your account.
/itemcloud list : You can see the list of all items in your account.
/itemcloud count <item id> : You can see your item count of specific item.

itemcloud.*
itemcloud.command.*
itemcloud.command.register
itemcloud.command.upload
itemcloud.command.download
itemcloud.command.list
itemcloud.command.count

Onebone