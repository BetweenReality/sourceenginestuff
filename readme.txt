Portal 2
	// Note: These dll's seem to have been updated since I modified them. Worst case scenario, there are a few bugs that aren't fixed (in recent Portal 2 updates). I'll modify the more up-to-date dll's eventually.
	Client.dll - sets the env_projectedtexture limit to 8 (Soft Limit)
	Server.dll - disables EnforceSingleProjectionRules()

The Stanley Parable
	Client.dll - sets the env_projectedtexture limit to 8 (Soft Limit)
	Server.dll - disables EnforceSingleProjectionRules(), re-enable sv_cheats
	Server.dll.serious - same as above, but also skips the call to load map seriousroom