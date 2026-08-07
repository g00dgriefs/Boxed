# Boxed

Simple Python utility to sort files in a folder.

## Usage

- `python sort_downloads.py` launches the GUI.
- `python sort_downloads.py /path/to/folder` sorts the folder from the command line.
- `python sort_downloads.py /path/to/folder --gui` opens the GUI with the folder already selected.
- `python sort_downloads.py --dry-run` previews without moving files.
- `python sort_downloads.py --install-context-menu` installs the Windows Explorer context menu entry.
- `python sort_downloads.py --uninstall-context-menu` removes the Windows Explorer context menu entry.

## Windows Explorer Context Menu

On Windows, launching the app normally will now also install `Sort Folder with Boxed` automatically if it is not already installed.

If you want to install it explicitly, run:

```powershell
python sort_downloads.py --install-context-menu
```

To remove the context menu entry later, run:

```powershell
python sort_downloads.py --uninstall-context-menu
```
