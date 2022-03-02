# Setting up EasyAdmin Permissions
```
# Here is where you setup your permissions for EasyAdmin to work, here's the available permission option's availabe below.

# add_ace group.ROLE easyadmin.player.ban.temporary
# add_ace group.ROLE easyadmin.player.ban.permanent
# add_ace group.ROLE easyadmin.player.ban.view
# add_ace group.ROLE easyadmin.player.ban.edit
# add_ace group.ROLE easyadmin.player.ban.remove
# add_ace group.ROLE easyadmin.player.kick
# add_ace group.ROLE easyadmin.player.spectate
# add_ace group.ROLE easyadmin.player.teleport.single
# add_ace group.ROLE easyadmin.player.teleport.everyone
# add_ace group.ROLE easyadmin.player.slap
# add_ace group.ROLE easyadmin.player.freeze
# add_ace group.ROLE easyadmin.player.mute
# add_ace group.ROLE easyadmin.player.warn
# add_ace group.ROLE easyadmin.player.screenshot (You will need screenshot-basic https://github.com/citizenfx/screenshot-basic)
# add_ace group.ROLE easyadmin.player.reports.view
# add_ace group.ROLE easyadmin.player.reports.claim
# add_ace group.ROLE easyadmin.player.reports.process

# **Server Permission's (For people you can trust)
# add_ace group.ROLE easyadmin.server.shortcut.add
# add_ace group.ROLE easyadmin.server.reminder.add
# add_ace group.ROLE easyadmin.server.permissions.read
# add_ace group.ROLE easyadmin.server.permissions.write
# add_ace group.ROLE easyadmin.server.cleanup.cars
# add_ace group.ROLE easyadmin.server.cleanup.props
# add_ace group.ROLE easyadmin.server.cleanup.peds

# **Server convars & resource operations are a very dangerous permission, only assign these to people you can REALLY trust.
# add_ace group.ROLE easyadmin.server.convars
# add_ace group.ROLE easyadmin.server.resources.start
# add_ace group.ROLE easyadmin.server.resources.stop
# add_ace group.ROLE easyadmin.server.server.chat

# Immune prevents you being kicked/banned by other admins, and anon is an anonymous admin feature, to hidde usernames in kicks/bans/admin logs.
# add_ace group.ROLE easyadmin.immune
# add_ace group.ROLE easyadmin.anon
```