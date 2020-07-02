# Announcement

- Directory structure
```
  .
  └── ${envs}                     <-- dev/sta/prod
      └── ${servers}              <-- 17app/event-server
          └── announcement.yaml   <-- conifguration
```

`announcement.yaml` contains information about the announcement, and also determines whether the shield server should send the announcement to the client.

## Templates

The templates of announcements are in [issues](https://github.com/17media/announcement/issues). If you want to revise the content of announcements, please update the templates. Next time the operator turns maintance on will use the new templates.
