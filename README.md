# App-Sync

This script can sync appdata from e.g. Logseq or Obsidian with git.

## Preparations

  - Clone this repo to e.g. `~/Apps/`:
    ```bash
    git clone https://github.com/brightdroid/app-sync.git ~/Apps/app-sync
    ```
  - Add symlink to `~/bin`:
    ```bash
    ln -st ~/bin ~/Apps/app-sync/app-sync
    ```

## Usage

After the preparation is done use the command `app-sync` to open e.g. Logseq or Obsidian with all your Graphs/Vaults.

### Example

Following example manages these Logseq-Graphs:
  - `~/Dokumente/logseq_graph1`
  - `~/Dokumente/logseq_graph2`

```bash
app-sync ~/bin/Logseq ~/Dokumente/logseq_graph1 ~/Dokumente/logseq_graph2
```

## Links

- [Git Icon](https://git-scm.com/downloads/logos) - CC BY 3.0
