# Spolszczenie [Fast Login](https://ci.codemc.io/job/Games647/job/FastLogin/changes) przez [vBagieta](https://github.com/vBagieta)

```
# FastLogin localization
# Project site: https://www.spigotmc.org/resources/fastlogin.14153
# Source code: https://github.com/games647/FastLogin
#
# You can access the newest locale here:
# https://github.com/games647/FastLogin/blob/main/core/src/main/resources/messages.yml
#
# You want to have language template? Visit the GitHub Wiki here:
# https://github.com/games647/FastLogin/wiki/English

# In order to split a message into separate lines you could just make a new line, but keep the '
# Example:
# bla: '&aFirst line
# Second line
# Third line'

# If you want to disable a message, you can just set it to a empty value.
# In this case no message will be sent
# Example:
# bla: ''

# ========= Shared (BungeeCord and Bukkit)   ============

# Switch mode is activated and a new cracked player tries to join, who is not namely allowed
switch-kick-message: '&eTylko gracze &6Premium&e mogą dołączyć'

# GameProfile activated premium login in order to skip offline authentication
add-premium: '&ePomyślnie włączono logowanie &6Premium'

# GameProfile activated premium login in order to skip offline authentication
add-premium-other: '&eGracz został dodany do graczy &6Premium'

# GameProfile is already set be a paid account
already-exists: '&eLogowanie &6Premium &ejest już włączone'

# GameProfile is already set be a paid account
already-exists-other: '&eTen gracz jest już dodany do graczy &6Premium'

# GameProfile was changed to be cracked
remove-premium: '&eGracz został usuniety z &6Premium'

# GameProfile is already set to be cracked
not-premium: '&eLogowanie &6Non-Premium było już właczone'

# GameProfile is already set to be cracked
not-premium-other: '&eGracz ma już włączone logowanie &6Non-Premium'

# Admin wanted to change the premium of a user that isn't known to the plugin
player-unknown: ' &eGracz nie jest w bazie danych'

# ========= Bukkit/Spigot ================

# The user skipped the authentication, because it was a premium player
auto-login: ' &eAutomatycze logowanie &6Premium'

# FastLogin attempted to auto register user. The user account is registered to protect it from cracked players
# If FastLogin is respecting auth plugin IP limit - the registration may have failed, however the message is still displayed
# The password can be used if the mojang servers are down and you still want your premium users to login (PLANNED)
auto-register: '&2Tried auto registering with password: &7%password&2. You may want change it?'

# GameProfile is not able to toggle the premium state of other players
no-permission: '&4Not enough permissions'

# Although the console can toggle the premium state, it's not possible for the console itself.
# Because the console is not a user. (obviously, isn't it?)
no-console: '&4You are not a player. You cannot toggle the premium state for YOURSELF as a console'

# The user wants to toggle premium state, but BungeeCord support is enabled. This means the server have to communicate
# with the BungeeCord first which will establish a connection with the database server.
wait-on-proxy: '&eWysyłanie zapytania do Proxy'

# When ProtocolLib is enabled and the plugin is unable to continue handling a login request after a requested premium
# authentication. In this state the client expects a success packet with a encrypted connection or disconnect packet.
# So we kick the player, if we cannot encrypt the connection. In other situation (example: premium name check),
# the player will be just authenticated as cracked
error-kick: '&4Error occurred'

# The server sends a verify token within the premium authentication request. If this doesn't match on response,
# it could be another client sending malicious packets
invalid-verify-token: '&4Invalid token'

# The client sent no request join server request to the mojang servers which would proof that it's owner of that
# account. Only modified clients would do this.
invalid-session: '&4Zla sesja'

# The client sent a malicious packet without a login request packet
invalid-requst: '&4Zla cos tam xD'

# Message if the Bukkit isn't fully started to inject the packets
not-started: '&cTrwa uruchamianie trybów. . .'

# Warning message if a user invoked /premium command
premium-warning: '&eTa komenda jest tylko dla graczy &6Premium&e! Wpisz ponownie &6/premium&e aby właczyc logowanie &6Premium&e!'

# ========= Bungee/Waterfall only ================================


