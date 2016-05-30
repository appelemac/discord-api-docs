Endpoints index generated with https://gist.github.com/SinisterRectus/b9d8b5d953558e6c3f82652e82671192

| Name                                                            | Method    | Endpoint                                              |
| --------------------------------------------------------------- | --------- | ----------------------------------------------------- |
| [Accept Invite](#INVITE/Accept-Invite)                          | POST      | /invites/{invite.id}                                  |
| [Ack Message](#CHANNEL/Ack-Message)                             | POST      | /channels/{channel.id}/messages/{message.id}/ack      |
| [Batch Modify Guild Role](#GUILD/Batch-Modify-Guild-Role)       | PATCH     | /guilds/{guild.id}/roles                              |
| [Begin Guild Prune](#GUILD/Begin-Guild-Prune)                   | POST      | /guilds/{guild.id}/prune                              |
| [Bulk Delete Messages](#CHANNEL/Bulk-Delete-Messages)           | POST      | /channels/{channel.id}/messages/bulk_delete           |
| [Create Channel Invite](#CHANNEL/Create-Channel-Invite)         | POST      | /channels/{channel.id}/invites                        |
| [Create DM](#USER/Create-DM)                                    | POST      | /users/@me/channels                                   |
| [Create Guild Ban](#GUILD/Create-Guild-Ban)                     | PUT       | /guilds/{guild.id}/bans/{user.id}                     |
| [Create Guild Channel](#GUILD/Create-Guild-Channel)             | POST      | /guilds/{guild.id}/channels                           |
| [Create Guild Integration](#GUILD/Create-Guild-Integration)     | POST      | /guilds/{guild.id}/integrations                       |
| [Create Guild Role](#GUILD/Create-Guild-Role)                   | POST      | /guilds/{guild.id}/roles                              |
| [Create Guild](#GUILD/Create-Guild)                             | POST      | /guilds                                               |
| [Create Message](#CHANNEL/Create-Message)                       | POST      | /channels/{channel.id}/messages                       |
| [Delete Channel Permission](#CHANNEL/Delete-Channel-Permission) | DELETE    | /channels/{channel.id}/permissions/{overwrite.id}     |
| [Delete Guild Integration](#GUILD/Delete-Guild-Integration)     | DELETE    | /guilds/{guild.id}/integrations/{integration.id}      |
| [Delete Guild Role](#GUILD/Delete-Guild-Role)                   | DELETE    | /guilds/{guild.id}/roles/{role.id}                    |
| [Delete Guild](#GUILD/Delete-Guild)                             | DELETE    | /guilds/{guild.id}                                    |
| [Delete Invite](#INVITE/Delete-Invite)                          | DELETE    | /invites/{invite.id}                                  |
| [Delete Message](#CHANNEL/Delete-Message)                       | DELETE    | /channels/{channel.id}/messages/{message.id}          |
| [Delete/Close Channel](#CHANNEL/Delete/Close-Channel)           | DELETE    | /channels/{channel.id}                                |
| [Edit Channel Permissions](#CHANNEL/Edit-Channel-Permissions)   | PUT       | /channels/{channel.id}/permissions/{overwrite.id}     |
| [Edit Message](#CHANNEL/Edit-Message)                           | PATCH     | /channels/{channel.id}/messages/{message.id}          |
| [Get Channel Invites](#CHANNEL/Get-Channel-Invites)             | GET       | /channels/{channel.id}/invites                        |
| [Get Channel Messages](#CHANNEL/Get-Channel-Messages)           | GET       | /channels/{channel.id}/messages                       |
| [Get Channel](#CHANNEL/Get-Channel)                             | GET       | /channels/{channel.id}                                |
| [Get Current User Guilds](#USER/Get-Current-User-Guilds)        | GET       | /users/@me/guilds                                     |
| [Get Current User](#USER/Get-Current-User)                      | GET       | /users/@me                                            |
| [Get Gateway](#GATEWAY/Get-Gateway)                             | GET       | /gateway                                              |
| [Get Guild Bans](#GUILD/Get-Guild-Bans)                         | GET       | /guilds/{guild.id}/bans                               |
| [Get Guild Channels](#GUILD/Get-Guild-Channels)                 | GET       | /guilds/{guild.id}/channels                           |
| [Get Guild Embed](#GUILD/Get-Guild-Embed)                       | GET       | /guilds/{guild.id}/embed                              |
| [Get Guild Integrations](#GUILD/Get-Guild-Integrations)         | GET       | /guilds/{guild.id}/integrations                       |
| [Get Guild Invites](#GUILD/Get-Guild-Invites)                   | GET       | /guilds/{guild.id}/invites                            |
| [Get Guild Member](#GUILD/Get-Guild-Member)                     | GET       | /guilds/{guild.id}/members/{user.id}                  |
| [Get Guild Prune Count](#GUILD/Get-Guild-Prune-Count)           | GET       | /guilds/{guild.id}/prune                              |
| [Get Guild Roles](#GUILD/Get-Guild-Roles)                       | GET       | /guilds/{guild.id}/roles                              |
| [Get Guild Voice Regions](#GUILD/Get-Guild-Voice-Regions)       | GET       | /guilds/{guild.id}/regions                            |
| [Get Guild](#GUILD/Get-Guild)                                   | GET       | /guilds/{guild.id}                                    |
| [Get Invite](#INVITE/Get-Invite)                                | GET       | /invites/{invite.id}                                  |
| [Get User DMs](#USER/Get-User-DMs)                              | GET       | /users/@me/channels                                   |
| [Get User](#USER/Get-User)                                      | GET       | /users/{user.id}                                      |
| [Get Users Connections](#USER/Get-Users-Connections)            | GET       | /users/@me/connections                                |
| [Leave Guild](#USER/Leave-Guild)                                | DELETE    | /users/@me/guilds/{guild.id}                          |
| [List Guild Members](#GUILD/List-Guild-Members)                 | GET       | /guilds/{guild.id}/members                            |
| [List Voice Regions](#VOICE/List-Voice-Regions)                 | GET       | /voice/regions                                        |
| [Modify Channel](#CHANNEL/Modify-Channel)                       | PUT/PATCH | /channels/{channel.id}                                |
| [Modify Current User](#USER/Modify-Current-User)                | PATCH     | /users/@me                                            |
| [Modify Guild Channel](#GUILD/Modify-Guild-Channel)             | PATCH     | /guilds/{guild.id}/channels                           |
| [Modify Guild Embed](#GUILD/Modify-Guild-Embed)                 | PATCH     | /guilds/{guild.id}/embed                              |
| [Modify Guild Integration](#GUILD/Modify-Guild-Integration)     | PATCH     | /guilds/{guild.id}/integrations/{integration.id}      |
| [Modify Guild Member](#GUILD/Modify-Guild-Member)               | PATCH     | /guilds/{guild.id}/members/{user.id}                  |
| [Modify Guild Role](#GUILD/Modify-Guild-Role)                   | PATCH     | /guilds/{guild.id}/roles/{role.id}                    |
| [Modify Guild](#GUILD/Modify-Guild)                             | PATCH     | /guilds/{guild.id}                                    |
| [Query Users](#USER/Query-Users)                                | GET       | /users                                                |
| [Remove Guild Ban](#GUILD/Remove-Guild-Ban)                     | DELETE    | /guilds/{guild.id}/bans/{user.id}                     |
| [Remove Guild Member](#GUILD/Remove-Guild-Member)               | DELETE    | /guilds/{guild.id}/members/{user.id}                  |
| [Sync Guild Integration](#GUILD/Sync-Guild-Integration)         | POST      | /guilds/{guild.id}/integrations/{integration.id}/sync |
| [Trigger Typing Indicator](#CHANNEL/Trigger-Typing-Indicator)   | POST      | /channels/{channel.id}/typing                         |
| [Upload File](#CHANNEL/Upload-File)                             | POST      | /channels/{channel.id}/messages                       |

