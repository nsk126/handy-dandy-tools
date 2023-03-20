# DISKPART

## Erasing entire device

1. In _CMD_ type `diskpart`.
2. In the terminal type -> `list disk`.
3. Select the disk # you want to delete. `select disk 1`
4. type `clean`.
5. Check if it worked by typing `list parititon`.
6. For new partition -> `create partition primary`.
7. Formatting: `format fs=fat32 quick`(_Change fat32 with anything you need_)
