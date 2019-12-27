
## Default Variables

### discord_started

Start in background after install

#### Default value

```yaml
discord_started: true
```

### discord_user

User to run user-specific commands

#### Default value

```yaml
discord_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
