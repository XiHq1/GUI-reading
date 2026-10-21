# 本地 PDF

本目录用于放论文 PDF，**不提交到 git**：一是版权原因，二是 14 篇约 180MB，超过普通仓库的合理体积。`.gitignore` 已排除 `papers/*.pdf`。

## 当前 14 篇

| 文件名 | 论文 |
|---|---|
| `2023_NeurIPS_Mind2Web.pdf` | Mind2Web |
| `2024_ACL_SeeClick.pdf` | SeeClick |
| `2024_ICLR_WebArena.pdf` | WebArena |
| `2024_NeruIPS_OSWorld.pdf` | OSWorld |
| `2025_CVPR_ShowUI.pdf` | ShowUI |
| `2025_ICCV_RegionFocus.pdf` | RegionFocus |
| `2025_ICLR_Agent S.pdf` | Agent S |
| `2025_ICLR_OS-ATLAS.pdf` | OS-Atlas |
| `2025_ICLR_UGround.pdf` | UGround |
| `2025_MM_ScreenSpot-Pro.pdf` | ScreenSpot-Pro |
| `2025_NeruIPS_OpenCUA.pdf` | OpenCUA |
| `2026_ACL_OS-Symphony.pdf` | OS-Symphony |
| `2026_ICLR_VideoAgentTrek.pdf` | VideoAgentTrek |
| `2026_ICML_GUI-Cursor.pdf` | GUI-Cursor |

## 从压缩包解压

```powershell
Expand-Archive -Path "$HOME\Desktop\论文阅读\1.GUI Agent论文整理.zip" -DestinationPath . -Force
```

解压后会多一层 `1.GUI Agent论文整理/`，把里面的 PDF 移到本目录即可。

## 为什么不用 Git LFS

LFS 仍然会把文件推到 GitHub，只是换个存储位置；版权问题没变。如果确实需要版本化 PDF，建议把仓库设为 **Private**，并且只放自己有权限分发的文献。
