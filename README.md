# Simple multiplayer

Developed with Unreal Engine 5.0.3

Simple multiplayer.
Change DefaultEngine.ini to run Steam.

===

[/Script/Engine.GameEngine]
+NetDriverDefinitions=(DefName="GameNetDriver",DriverClassName="OnlineSubsystemSteam.SteamNetDriver",DriverClassNameFallback="OnlineSubsystemUtils.IpNetDriver")

[OnlineSubsystem]
DefaultPlatformService=Steam
