# Security

TG LinkKit is a local Telegram client plugin.

It does not use:

- external APIs;
- tokens;
- passwords;
- telemetry;
- servers;
- Bot API.

The plugin reads only the current chat/profile context exposed by the client runtime and copies selected text to the local clipboard.

## Notes

Be careful when sharing copied output from Ultimate dossier or debug formats: those formats may include numeric IDs or other client-visible profile fields.

Please do not publish private chat dumps, session files, tokens, or private keys in issues.
