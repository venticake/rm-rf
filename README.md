# rm-rf

A playful, conservative disk cleaner for macOS and Ubuntu.

```sh
./rm-rf
```

Run it, pick items with `Space`, then press `Enter` to delete them.

It only scans known cleanup areas. Deletion always requires typing `DELETE`.

## At a glance

See free space, recommended reclaim, selected items, and each candidate's priority in one terminal screen.

![rm-rf overview](docs/screenshots/overview.png)

Press `i` for the item's path, what it is, why it is safe or risky to remove, and the cleanup rationale.

![rm-rf candidate details](docs/screenshots/details.png)

## Advanced

- Scan results expire after **24 hours** and refresh automatically. Use `--cache-ttl-hours 6` to change it, or `0` to always rescan.
- Press `r` to rescan now, `i` for item details, and `a` for a Claude review of the focused item.
