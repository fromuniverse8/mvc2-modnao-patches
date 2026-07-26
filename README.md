# MVC2 ModNao Patches

A temporary home for ready-to-use [ModNao](https://modnao.vercel.app) patches
for **Marvel vs. Capcom 2**.

## How to Use These Patches

You will need files extracted from your own copy of MVC2. Back them up before
you start.

1. Download a patch from the list below. Do not extract or rename the
  `.mnp.zip` file.
2. Find the patch's **Files to load** in the table.
3. Open [ModNao](https://modnao.vercel.app) and click **Import files**.
4. Select all of the listed files together.
5. Click **Import files** again and select the `.mnp.zip` patch **by itself**.
6. Click **Export Models** for a listed POL file and **Export Texture BIN** for
  a listed TEX file.
7. ModNao adds `.mn` to each exported filename. Remove `.mn`, replace the
   matching original files, then add them back to your game.

Example: rename `STG0BPOL.mn.BIN` back to `STG0BPOL.BIN` before replacing the
original.

### Patch Your Game

- For Dreamcast, follow the process listed in
  [ModNao](https://modnao.vercel.app).
- For MVCC, follow
  [Paxtez' MVCC Mod Manager tutorial](https://youtu.be/WP_ALj4g5K8).

## Patches

| Preview | Patch | Files to load | Creator |
| --- | --- | --- | --- |
| <img src="./stg05.coral-cave.png" alt="Coral Cave Stage in gameplay" width="320"> | **Coral Cave Stage**<br>Coral-toned cave with bright blue water. The floating grave now says "Where's mahvel" in Japanese (made pre-MVCC)<br><br>[Download patch](./stg05.coral-cave.mnp.zip) | `STG05POL.BIN`<br>`STG05TEX.BIN` | rob2d |
| <img src="./stg09.psychadelic-dark.png" alt="Psychedelic dark Airship Stage in gameplay" width="320"> | **Psychedelic Dark Airship Stage**<br>Dark Airship stage with vivid neon colors.<br><br>[Download patch](./stg09.psychadelic-dark.mnp.zip) | `STG09POL.BIN`<br>`STG09TEX.BIN` | rob2d |
| <img src="./stg0b.purple-blue-dark-training.png" alt="Purple and blue dark Training Stage in gameplay" width="320"> | **Purple/Blue Dark Training Stage**<br>Dark background with a purple and blue grid.<br><br>[Download patch](./stg0b.purple-blue-dark-training.mnp.zip) | `STG0BPOL.BIN`<br>`STG0BTEX.BIN` | rob2d |
| <img src="./stg0b.red-tech.png" alt="Red Tech Training Stage in gameplay" width="320"> | **Red Tech Training Stage**<br>Dark red grid with a glowing orange platform.<br><br>[Download patch](./stg0b.red-tech.mnp.zip) | `STG0BPOL.BIN`<br>`STG0BTEX.BIN` | rob2d |

## Contributing Patches

Pull requests with new patches are welcome! Include the `.mnp.zip` as exported by ModNao, an in-game PNG preview, and a matching row in the table above.

For stage patches, a matching SELSTG texture patch is also welcome if you have one.

**Please do not include copyrighted game files or unrelated third-party IP.
Include only the minimum files needed for the patch, preview, and table entry.**

## Having Trouble?

- **Patch will not import:** Load the listed original files first, then choose
  only the `.mnp.zip` file on the second import.
- **ModNao says the patch is for a different resource:** Make sure you loaded
  the exact original files listed for that patch.
- **The stage is only partly changed:** Export and replace every file listed
  under **Files to load**.
- **You want to go back:** Restore the backups of your original files.

No game files are included. These patches only work with files extracted from
your own copy of MVC2.
