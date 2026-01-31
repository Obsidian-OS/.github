# [ObsidianOS](https://obsidianos.xyz)
ObsidianOS is a GNU/Linux **meta**-distro with an A/B partition style so if a package has a breaking change that causes some issues, you can just reboot into the other partition and restore the other one, while relying on the robustness of EXT4 (or f2fs!).

To install ObsidianOS right now, no download needed:
```bash
sudo bash -c "$(curl -fsSL https://arbs.obsidianos.xyz)"
```
(requires the arch-install-scripts package)

To download an ObsidianOS ISO:
```bash
bash -c "$(curl -fsSL https://bdj.obsidianos.xyz/)"
```

## License
All of ObsidianOS's tooling is licensed under MIT.
<details> <summary>
  Exceptions
</summary>
  
- [ObsidianOS KCM (GPL3)](https://github.com/Obsidian-OS/kcm)

</details>

[![Try ObsidianOS](https://img.shields.io/badge/Try-ObsidianOS-400080?labelColor=%23333333)](https://obsidianos.xyz/)
