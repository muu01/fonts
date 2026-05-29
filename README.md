# fonts

A personal font backup repository — collected and stored here after setting up a new MacBook.

## Note on Licensing

These fonts come from a variety of sources and may carry different licenses. Before using any font from this repository — especially in commercial projects — please check the individual license for that font. Some are free for personal use only, some are trial versions, and some are fully open source.

## Cloning

Some files in this repository are large and tracked with Git LFS (Large File Storage). Without LFS installed, those files will clone as small pointer files rather than the actual font data.

Install Git LFS before cloning:

```bash
# macOS
brew install git-lfs

# or via the installer at https://git-lfs.com
git lfs install
```

Then clone and pull LFS objects:

```bash
git clone https://github.com/muu01/fonts
cd fonts
git lfs pull
```

If you already cloned without LFS and are seeing placeholder files, run:

```bash
git lfs install
git lfs pull
```

To check which files are tracked by LFS in this repo:

```bash
git lfs ls-files
```
