Portal 2
	// Note: These dll's seem to have been updated since I modified them. Worst case scenario, there are a few bugs that aren't fixed (in recent Portal 2 updates). I'll modify the more up-to-date dll's eventually.
	Client.dll - sets the env_projectedtexture limit to 8 (Soft Limit)
	Server.dll - disables EnforceSingleProjectionRules()

The Stanley Parable
	Client.dll - sets the env_projectedtexture limit to 8 (Soft Limit)
	Client.dll.jump - re-enables jumping as well
	Server.dll - disables EnforceSingleProjectionRules(), re-enable sv_cheats
	Server.dll.serious - same as above, but also skips the call to load map seriousroom

Relevant Reddit Posts:
	https://reddit.com/r/stanleyparable/comments/1b6k8ki/native_reenabled_jumping_in_the_stanley_parable/
	https://reddit.com/r/stanleyparable/comments/1awk8pl/patched_clientdll_and_serverdll_to_increase_env/
