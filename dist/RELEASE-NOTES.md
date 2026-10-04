ARA Connect — Powered by AllStarLink

User Mode: full-width bottom talk bar with a white rounded outline. Red while holding Space or mouse to transmit, amber during incoming voice, navy when idle. Shows transmitting/receiving node identity or number of destinations. Independent 90-second transmit limit; release resets it. Losing focus unkeys and requires release before restarting.

USB/COR/PL indicators hidden in User Mode, retained in Link Mode. Clear running/connecting/connected status. Audio & Radio adds a local 10-second microphone level check; no network transmission. Logs & Tests adds Open logs and Copy diagnostics without credentials. Window size/position remembered and moved onto an available screen. Connected exit prompts to disconnect; transmit releases before the prompt.

Quiet Windows now targets only the Windows system-sounds session, preserving ARA and other application audio and restoring original mute states on disable/stop/close. Corrected the invalid IMMDeviceCollection interface ID behind E_NOINTERFACE. Newly created system-sounds sessions are polled. Application-specific notification audio is outside the Windows system-sounds session.

Build and engine/mocked mute/UI tests passed. Native Windows audio/muting/keyboard/USB and an overnight soak test remain for field verification.

Close ARA Connect before installing over the existing version. Settings preserved; no uninstall required. Installer unsigned; automatic installation remains disabled pending trusted signing.