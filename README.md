# vRP_itemdrop
The module for vRP, which when throwing an object on the ground creates a package on the ground, in which the discarded objects will be stored.

# Install
Unpack the module in the folder vRP_itemdrops, connect to the server.sfg through the start vRP_itemdrops.
Also add the TriggerClientEvent ("DropSystem: drop", player, idname, amount) to the vrp/modules/inventory.lua
